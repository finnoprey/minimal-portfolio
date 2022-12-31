<style>
  @import url('https://fonts.googleapis.com/css2?family=Vollkorn:ital,wght@0,400;0,500;0,600;0,700;0,800;1,400;1,500;1,600;1,700;1,800&display=swap');

  :root {
    --color-theme: rgb(223, 100, 43);
    --color-background: rgb(247, 247, 247);
    --color-background-extreme: rgb(255, 255, 255);
    --color-text-main: rgb(0, 0, 0);
    --color-text-accent: rgb(255, 255, 255);
  }

  * {
    font-family: 'Vollkorn', serif;
  }

  :global(body) {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    background-color: var(--color-background);
  }



  a {
    color: var(--color-theme);
    text-decoration-line: underline;
    text-decoration-style: dashed;
    text-decoration-thickness: 1px; 
  }

  .content {
    width: min(820px, 100%);
  }

  .table {
    background-color: white;
    color: var(--color-text-main);
  }

  .table-box {
    width: min(400px, 100%);
  }

  h2 {
    color: var(--color-text-main);
    margin: 0;
  }

  table {
    width: 100%;
    border-collapse: collapse;
    table-layout: fixed;
  }

  thead {
    width: 100%;
    background-color: var(--color-theme);
    color: var(--color-text-accent) !important;
  }

  tr {
    border-width: 1px;
    border-color: black;
    border-style: solid;
    border-radius: 10px;
  }

  td {
    padding: 4px;
    width: 35%;
  }

  td+td {
    width: auto;
  }

  .info-box {
    margin-top: 20px;
    display: flex;
    align-items: baseline;
    align-content: flex-start;
    justify-content: flex-start;
    gap: 20px 20px;
    flex-direction: row;
    flex-wrap: wrap;
  }

</style>

<svelte:head>
    <title>finn [~/]</title> 
</svelte:head>

<div class="content">
  <p>~/</p>
  <hr>
  <div class="info-box">
    <div class="table-box">
      <table class="table">
        <thead>
          <tr>
            <td>About</td>
            <td></td>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>Name</td>
            <td class="td-answer">Finn Scicluna-O'Prey</td>
          </tr>
          <tr>
            <td>Age</td>
            <td>17</td>
          </tr>
          <tr>
            <td>Location</td>
            <td>Melbourne, Australia</td>
          </tr>
        </tbody>
      </table>
    </div>
    <div class="table-box">
      <table class="table">
        <thead>
          <tr>
            <td>Contact</td>
            <td></td>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>Email</td>
            <td>finn@oprey.co</td>
          </tr>
          <tr>
            <td>Github</td>
            <td><a href="https://github.com/finnoprey">finnoprey</a></td>
          </tr>
        </tbody>
      </table>
    </div>
    <div class="table-box">
      <table class="table">
        <thead>
          <tr>
            <td>Projects</td>
            <td></td>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>Phone Number to Words</td>
            <td><a href="https://pntw.finn.so">pntw.finn.so</a></td>
          </tr>
          <tr>
            <td>IP Lookup</td>
            <td><a href="https://ip.finn.so">ip.finn.so</a></td>
          </tr>
          <tr>
            <td>Clive Inc.</td>
            <td><a href="https://shutupc.live">shutupc.live</a></td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>
</div>