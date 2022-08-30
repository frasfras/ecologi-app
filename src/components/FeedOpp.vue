<template>
  <div class="container">
    <iframe src="http://127.0.0.1:1880/" width="500" height="500" />>
    <div class="row">
      <div class="col-md-6 h1">
        <table class="table">
          <thead>
            <tr>
              <th scope="col">Name</th>
              <th scope="col">Url</th>
              <th scope="col"></th>
            </tr>
          </thead>
          <tbody>
            <tr class="table-primary">
              <td>name</td>
              <td>url</td>
              <td>
                <a href="/monitor/feed/delete/" class="btn btn-outline-danger"
                  >delete</a
                >
              </td>
            </tr>
          </tbody>
        </table>
      </div>
      <div class="col-md-6">
        <form method="POST" action="http://127.0.0.1:1880/monitor/feed">
          <label for="name">Name</label>
          <input class="form-control" id="name" name="name" />
          <label for="url">Url</label>
          <input class="form-control" id="url" name="url" />
          <button type="submit" class="btn btn-primary">Add</button>
        </form>
      </div>
    </div>
  </div>
</template>

<script>
//import HelloWorld from "../components/PlanView";
//import HelloWorld from "../components/BnbDeal";

/* eslint-disable */ 
  export default {
    name: 'FeedOpp',

    components: {
     
    },
  }
</script>
<style>
knob-label {
    display: block;
    margin-bottom: 0;
    font-weight: bold;
     color: #febc2c;
}
</style>

