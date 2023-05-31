# projeto-vercel no git feito em React
## simples, somente é feito um fetch em:
 async function buscarDados() {
      fetch('https://jsonplaceholder.typicode.com/todos')
      .then(res => res.json())
      .then(res => setTarefas(res))
    }
