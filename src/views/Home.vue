<template>
  <div>
    <div class="container">
      <!-- collapsible -->
      <div class="row">
        <div class="col m6 s12">
          <ul class="collapsible">
            <Collapsible title="DSLR" description="DSLR" />
            <Collapsible title="Video Cameras" description="Video Cameras" />
            <Collapsible title="Camera Tripods" description="Camera Tripods" />
            <Collapsible title="Video Tripods" description="Video Tripods" />
            <Collapsible title="Lightning" description="Lightning" />
            <Collapsible title="Microphones" description="Microphones" />
            <Collapsible title="Accessories" description="Accessories" />
            <Collapsible title="Rooms" description="Rooms" />
          </ul>
        </div>
        <div class="col m6 s12">
          <ul class="collapsible">
            <Collapsible
              title="My Borrowed Items"
              description="No Items Borrowed Yet."
            />
          </ul>
        </div>
      </div>
      <!-- collapsing end -->
    </div>
    <Footer />
  </div>
</template>

<script>
import M from "materialize-css";
import Collapsible from "../components/Collapsible";
import Footer from "../components/Footer";
export default {
  name: "Home",
  methods: {},
  mounted() {
    M.AutoInit();
  },
  components: {
    Collapsible,
    Footer,
  },
};
</script>
