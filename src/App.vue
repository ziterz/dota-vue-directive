<template>
  <div>
    <div class="container">
      <div class="row">
        <div class="col-6 offset-3 mt-4">
          <div class="card">
            <div class="card-body">
              <h5 class="card-title">Choose your hero</h5>
              <form>
                <div class="form-group row">
                  <label for="name" class="col-3 col-form-label">Hero Name</label>
                  <div class="col-9">
                    <input type="text" class="form-control" id="name">
                  </div>
                </div>
                <div class="form-group row">
                  <label for="type" class="col-3 col-form-label">Type</label>
                  <div class="col-9">
                    <select class="form-control" id="type">
                      <option>Strength</option>
                      <option>Agility</option>
                      <option>Intelligence</option>
                    </select>
                  </div>
                </div>
                <div class="form-group row">
                  <label for="image" class="col-3 col-form-label">Image URL</label>
                  <div class="col-9">
                    <input type="text" class="form-control" id="image">
                  </div>
                </div>
                <div class="form-group row">
                  <div class="col-10">
                    <button type="submit" class="btn btn-primary">Pick Hero</button>
                  </div>
                </div>
              </form>
            </div>
          </div>
        </div>
      </div>
      <div class="row mt-4">
        <div class="col-12">
          <h5>Hero List</h5>
        </div>
      </div>
      <div class="row">
        <div class="col-3 mb-3">
          <div class="card">
            <img src="https://gamepedia.cursecdn.com/dota2_gamepedia/c/c0/Pudge_icon.png" class="card-img-top">
            <div class="card-body">
              <h5 class="card-title">Pudge</h5>
              <p class="card-text"><img src="https://gamepedia.cursecdn.com/dota2_gamepedia/7/7a/Strength_attribute_symbol.png" width="24" height="24"> Strength</p>
            </div>
          </div>
        </div>
        <div class="col-3 mb-3">
          <div class="card">
            <img src="https://gamepedia.cursecdn.com/dota2_gamepedia/8/8a/Rubick_icon.png" class="card-img-top">
            <div class="card-body">
              <h5 class="card-title">Rubick</h5>
              <p class="card-text"><img src="https://gamepedia.cursecdn.com/dota2_gamepedia/5/56/Intelligence_attribute_symbol.png" width="24" height="24"> Intelligence</p>
            </div>
          </div>
        </div>
        <div class="col-3 mb-3">
          <div class="card">
            <img src="https://gamepedia.cursecdn.com/dota2_gamepedia/3/36/Shadow_Fiend_icon.png" class="card-img-top">
            <div class="card-body">
              <h5 class="card-title">Shadow Fiend</h5>
              <p class="card-text"><img src="https://gamepedia.cursecdn.com/dota2_gamepedia/2/2d/Agility_attribute_symbol.png" width="24" height="24"> Agility</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data () {
    return {
      message: 'Hello world!'
    }
  }
}
</script>

<style>
.card {
  -webkit-box-shadow: 0 0.15rem 1.75rem 0 rgba(31,45,65,.15);
  box-shadow: 0 0.15rem 1.75rem 0 rgba(31,45,65,.15);
  overflow: hidden;
  position: relative;
  border: 0;
}
</style>