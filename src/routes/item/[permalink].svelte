<script context="module">
    import db from '$lib/db'
  
    export async function load({page}) {
      // find the publicTable
      const publicTable = await db.publicTable.find(page.params.permalink)
  
      // if we found it, return it as a prop
      if (publicTable) {
        return {
          props: {
            publicTable
          }
        }
      }
  
      // oh shoot, we didn't find a publicTable, so return 404
      return {
        status: 404,
        error: new Error('publicTable not found')
      }
    }
  </script>
  
  <script>
    // this prop will be provided by the `load` function
    export let publicTable
  </script>
  
  <h1>{publicTable.name}</h1>
  <p>SKU: {publicTable.sku}</p>
  
  <p>{publicTable.details}</p>
  
  {publicTable.price}