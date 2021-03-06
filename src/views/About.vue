<template>
  <div class="container-fluid mt-4">
    <div class="row p-4 pb-0">
      <div class="col-xl-6 grey grey lighten-4 elevation-2 rounded-lg">
        <h5>About The Circular Economy Toolkit</h5>
        <p>
          This toolkit is one of the products of an ongoing R+D effort by
          Cuningham. This work reflects a broader push across our studios and
          design practices to embody the principles of regenerative design.
        </p>
        <p>
          This toolkit grew out of internal research efforts that included an
          extensive literature review, a self assessment of several of our past
          designs, and internal deliberations regarding how circularity can
          begin to be implemented in conventional design projects. Currently
          this toolkit includes an interactive diagram that visualizes common
          ways circular economy principles can be applied in the built
          environment, and links to numerous external resources that can help
          someone get up to speed on the details of these topics.
        </p>
      </div>
    </div>
    <div class="row p-4 pb-0">
      <div class="col-xl-6 grey grey lighten-4 elevation-2 rounded-lg">
        <h5>Future Development Goals</h5>
        <p>
          This site is under continued development, and the next major
          development push is planning to include the following features...
        </p>
        <ul>
          <li>
            A set of pages for selecting circular design goals for a given
            project
          </li>
          <li>
            A set of pages for tracking a project's delivery on its circular
            design goals
          </li>
        </ul>
      </div>
    </div>
    <div class="row p-4 pb-0">
      <div class="col-xl-6 grey grey lighten-4 elevation-2 rounded-lg">
        <h5>Contribute Ideas</h5>
        <p>
          We are building a form that will allow you to contribute your insights
          and ideas to this project. This feature is coming soon!
        </p>
      </div>
    </div>
    <div class="row p-4 pb-0">
      <div class="col-xl-6 grey grey lighten-4 elevation-2 rounded-lg">
        <h5>Get in Touch</h5>
        <p>
          We are always looking for new partners and collaborators in our work
          to improve the built environment. We are planning to build a contact
          form, but for the meantime reach out to Cuningham and we will make
          sure you get in touch with the right people!
        </p>
      </div>
    </div>
    <div class="row p-4 pb-0">
      <div class="col-xl-6 grey grey lighten-4 elevation-2 rounded-lg">
        <div class="container m-0 p-0">
          <div class="row m-0 p-0">
            <div class="col-8 m-0 p-0">
              <h5>Open Source</h5>
              <p>
                This toolkit is being developed as open source software, and is
                licensed with an MIT License.
              </p>
              <v-btn
                class="mt-0 pt-0 elevation-4"
                color="grey darken-3"
                dark
                outlined
                @click="openGithubLink()"
              >
                <v-icon class="pr-2">mdi-github</v-icon>
                Source Code
              </v-btn>
            </div>
            <div class="col-4"></div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "About",
  methods: {
    openGithubLink() {
      window.open(
        "https://github.com/dschipperCuningham/Circular-Economy-Design-Principles",
        "_blank"
      );
    }
  }
};
</script>
