<template>
  <div class="row">
    <div class="col-12 ImgHome">
      <div class="row contatos">
        <q-icon name="forward_to_inbox" size="32px" />
        <div class="col-2">
          <div class="row">
            <p class="card-text">info@example.com</p>
          </div>
        </div>
        <div class="col-5">
          <div class="row">
            <q-icon name="call" size="32px" />
            <p class="card-text">+1 5589 55488 55</p>
          </div>
        </div>
        <div class="col-3">
          <div class="row">
            <q-btn
              no-caps
              text-color="black"
              icon="lock"
              color="yellow-14"
              label="Aria
              restrita"
            />
          </div>
        </div>
      </div>
      <div class="q-pa-md">
        <q-toolbar class="bg-light-blue-10 text-white">
          <div class="col-1">
            <a href="#"><q-toolbar-title>ANYAR</q-toolbar-title></a>
          </div>
          <a class="linksMenu" href="#">Home</a>
          <a class="linksMenu" href="#">About</a>
          <a class="linksMenu" href="#">Services</a>
          <a class="linksMenu" href="#">Portfolio</a>
          <a class="linksMenu" href="#">Team</a>
          <a class="linksMenu" href="#">Pricing</a>
          <a class="linksMenu" href="#">Blog</a>
          <q-btn-dropdown color="primary" label="Drop Down">
            <q-list>
              <q-item clickable v-close-popup @click="onItemClick">
                <q-item-section>
                  <q-item-label>Photos</q-item-label>
                </q-item-section>
              </q-item>

              <q-item clickable v-close-popup @click="onItemClick">
                <q-item-section>
                  <q-item-label>Videos</q-item-label>
                </q-item-section>
              </q-item>

              <q-item clickable v-close-popup @click="onItemClick">
                <q-item-section>
                  <q-item-label>Articles</q-item-label>
                </q-item-section>
              </q-item>
            </q-list>
          </q-btn-dropdown>
          <a class="linksMenu" href="#">Contact</a>
        </q-toolbar>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "IndexPage",
};
</script>

<style scoped>
a {
  color: aliceblue;
  text-decoration: none;
}
.ImgHome {
  background-image: url(https://images6.alphacoders.com/774/774373.jpg);
  height: 600px;
}

.contatos {
  margin: 20px 0 0 60px;
  color: aliceblue;
}

.card-text {
  margin: 5px 0 0 0;
  color: aliceblue;
}

.linksMenu {
  margin: 0 20px 0 0;
}
</style>

<script></script>
