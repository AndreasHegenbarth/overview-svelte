<script>
    let email = '';
    let password = '';
  
    function handleLogin() {
      // Login Logik hier einfügen
    }
  </script>
  
  <form on:submit|preventDefault={handleLogin}>
    <label>
      Email:
      <input type="email" bind:value={email} />
    </label>
    <label>
      Passwort:
      <input type="password" bind:value={password} />
    </label>
    <button type="submit">Login</button>
  </form>
  
  <style>
    form {
      display: flex;
      flex-direction: column;
      gap: 1rem;
    }
    label {
      display: flex;
      flex-direction: column;
    }
  </style>
  