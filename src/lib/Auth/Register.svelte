<script>
    let email = '';
    let password = '';
  
    function handleRegister() {
      // Registrierungslogik hier einfügen
    }
  </script>
  
  <form on:submit|preventDefault={handleRegister}>
    <label>
      Email:
      <input type="email" bind:value={email} />
    </label>
    <label>
      Passwort:
      <input type="password" bind:value={password} />
    </label>
    <button type="submit">Registrieren</button>
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
  