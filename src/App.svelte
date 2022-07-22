<script lang="ts">
  import svelteLogo from '/assets/svelte.svg'
  import Counter from './lib/Counter.svelte'
</script>

<main>
  <div>
    <a href="https://vitejs.dev" target="_blank"> 
      <img src="/vite.svg" class="logo" alt="Vite Logo" />
    </a>
    <a href="https://svelte.dev" target="_blank"> 
      <img src={svelteLogo} class="logo svelte" alt="Svelte Logo" />
    </a>
  </div>
  <h1>Vite + Svelte</h1>
  
  <div class="card">
    <Counter />
  </div>
  
  <p>
    Check out <a href="https://github.com/sveltejs/kit#readme" target="_blank">SvelteKit</a>, the official Svelte app framework powered by Vite!
  </p>
  
  <p class="read-the-docs">
    Click on the Vite and Svelte logos to learn more
  </p>
</main>


<header class="header">
  <h1 class="title">dev.finance$</h1>
</header>

<main class="main">
  <section class="balance-section">
    <h2 class="balance">Balanço</h2>
    
    <div class="card">
      <h3 class="entrys">Entradas</h3>
      <p class="value">R$ 5.000,00</p>
    </div>
    
    <div class="card">
      <h3 class="exits">Saídas</h3>
      <p class="value">R$ 2.000,00</p>
    </div>
    
    <div class="card">
      <h3 class="total">Total</h3>
      <p class="value">R$ 3.000,00</p>
    </div>
    
  </section>
  
  <section class="transaction-section">
    <h2 class="transactions">Transações</h2>
    
    <table>
      <thead>
        <tr>
          <th>Descrição</th>
          <th>Valor</th>
          <th>Data</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Luz</td>
          <td>- R$ 500,00</td>
          <td>23/01/2021</td>
        </tr>
        <tr>
          <td>Criação Website</td>
          <td>R$ 5000,00</td>
          <td>23/01/2021</td>
        </tr>
        <tr>
          <td>Internet</td>
          <td>R$ 200,00</td>
          <td>23/01/2021</td>
        </tr>
      </tbody>
    </table>
  </section>     
  
</main>

<footer class="footer">
  <p class="footer-paragraph">dev.finance$ </p> 
</footer>



<style>
  .logo {
    height: 6em;
    padding: 1.5em;
    will-change: filter;
  }
  .logo:hover {
    filter: drop-shadow(0 0 2em #646cffaa);
  }
  .logo.svelte:hover {
    filter: drop-shadow(0 0 2em #ff3e00aa);
  }
  .read-the-docs {
    color: #888;
  }
</style>