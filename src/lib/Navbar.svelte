<script>
    let links = [
      { name: 'Home', href: '/' },
      { name: 'Dashboard', href: '/dashboard' },
      { name: 'Account', href: '/account' },
      { name: 'Portals', href: '/portals' },
      { name: 'Appointments', href: '/appointments' },
      { name: 'Documents', href: '/documents' },
      { name: 'Notes', href: '/notes' },
    ];
  </script>
  
  <nav>
    <ul>
      {#each links as link}
        <li><a href={link.href}>{link.name}</a></li>
      {/each}
    </ul>
  </nav>
  
  <style>
    nav {
      background: #343a40;
      color: white;
      padding: 1rem;
    }
    ul {
      list-style: none;
      padding: 0;
      display: flex;
      gap: 1rem;
    }
    a {
      color: white;
      text-decoration: none;
    }
  </style>
  