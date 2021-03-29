<template>
  <div class="dashboard">
    <div class="main_info">
      <span class="img"></span>
      <div class="info_personne">
        <h1 class="subtitle-1 grey--text name">Salut monther saeed</h1>
        <span class="subtitle-1 grey--text font-weight-black"
          >Hamilton 4.25</span
        >
        <v-icon mr-0 large>code</v-icon>
      </div>
    </div>
    <!-- Start Container -->
    <v-container class="my-5">
      <h2 class="grey--text body-1 font-weight-bold">Attendances</h2>
      <p class="grey--text body-2 mb-4">
        Use the following buttons at the right moment to encode your
        attendances.
      </p>
      <!-- Start Card -->
      <v-card flat color="grey lighten-4" class="pa-4">
        <v-row>
          <v-col cols="12" class="hidden-sm-and-down" md="4">
            <h3 class="caption grey--text text-capitalize">my location</h3>
            <v-btn outlined color="grey " class="mr-2">
              <v-icon left class="orange--text">apartment</v-icon>
              becode</v-btn
            >
            <v-btn outlined color="grey ">
              <v-icon left class="orange--text">home</v-icon>
              Home</v-btn
            >
          </v-col>
          <v-col cols="3" class="hidden-sm-and-down" md="2">
            <h3 class="caption grey--text text-capitalize">morning</h3>
            <v-btn outlined color="grey ">
              <v-icon left class="orange--text">alarm_on</v-icon>
              09:00</v-btn
            >
            <h4 class="caption grey--text text-capitalize">
              Active from <span class="orange--text">09:00</span> to
              <span class="orange--text">12:00</span>
            </h4>
          </v-col>
          <v-col cols="3" class="hidden-sm-and-down" md="2">
            <h3 class="caption grey--text text-capitalize">lunch</h3>
            <v-btn outlined color="grey ">
              <v-icon left class="orange--text">alarm_on</v-icon>
              12:01</v-btn
            >
            <h4 class="caption grey--text text-capitalize">
              Active from <span class="orange--text">09:00</span> to
              <span class="orange--text">12:00</span>
            </h4>
          </v-col>
          <v-col cols="3" class="hidden-sm-and-down" md="2">
            <h3 class="caption grey--text text-capitalize">noon</h3>
            <v-btn outlined color="grey ">
              <v-icon left class="orange--text">alarm_on</v-icon>
              13:30</v-btn
            >
            <h4 class="caption grey--text text-capitalize">
              Active from <span class="orange--text">13:20</span> to
              <span class="orange--text">17:00</span>
            </h4>
          </v-col>
          <v-col cols="3" class="hidden-sm-and-down" md="2">
            <h3 class="caption text-capitalize grey--text">evning</h3>
            <v-btn outlined color="grey ">
              <v-icon left class="orange--text">alarm_on</v-icon>
              17:00</v-btn
            >
            <h4 class="caption grey--text text-capitalize">
              Active from <span class="orange--text">13:30</span> to
              <span class="orange--text">21:00</span>
            </h4>
          </v-col>
        </v-row>
      </v-card>
      <!-- End Card -->
      <p class="grey--text body-2 mt-4">
        Missed a checkpoint? Contact your coaches as soon as you can!
      </p>
      <!-- Start Second Card -->
      <v-card flat color="grey lighten-4" class="pa-4">
        <v-row>
          <!-- Start First Column -->
          <v-col cols="12" md="4">
            <h2 class="grey--text body-1 mb-5">
              <v-icon left class="orange--text">hourglass_bottom</v-icon>
              Absences to justify
            </h2>
            <h3 class="grey--text body-2 mb-2">
              Overall attendance rate: 99.12%
            </h3>
            <v-progress-linear color="grey" height="25" class="mb-3" />
            <h3 class="grey--text body-2">
              OAR must stay above 80% or contract can be terminated.
            </h3>
            <v-btn outlined class="grey--text my-3">
              <v-icon left class="orange--text">add_circle_outline</v-icon>
              record an Absences</v-btn
            >
            <h3 class="grey--text body-2">
              The following absences needs to be justified:
            </h3>
            <v-card flat color="grey lighten-2" class="my-3">
              <v-list-item>
                <v-list-item-content>
                  <v-list-item-title class="font-weight-bold grey--text"
                    >28 Dec 2020</v-list-item-title
                  >
                  <hr />
                  <v-list-item-title class="mt-3 grey--text"
                    >Morning: 12:24</v-list-item-title
                  >
                  <v-list-item-title class="my-2 grey--text"
                    >Lunch: 12:30</v-list-item-title
                  >
                  <v-list-item-title class="mb-2 grey--text"
                    >Noon: 13:30</v-list-item-title
                  >
                  <v-list-item-title class="grey--text"
                    >Evening: 17:00</v-list-item-title
                  >
                </v-list-item-content>
              </v-list-item>
              <v-btn outlined class="grey--text my-3 ml-3">
                <v-icon left class="orange--text">add_circle_outline</v-icon>
                justify my absence for this day</v-btn
              >
              <hr />
              <v-list-item>
                <v-list-item-content>
                  <v-list-item-title class="font-weight-bold grey--text"
                    >5 Oct 2020</v-list-item-title
                  >
                </v-list-item-content>
              </v-list-item>
            </v-card>
            <v-btn outlined class="grey--text my-3 ml-3">
              <v-icon left class="orange--text">import_contacts</v-icon>
              review past absence</v-btn
            >
          </v-col>

          <!-- End First Column -->
          <!-- Start Second Column -->
          <v-col cols="12" md="4" class="text-center">
            <h2 class="grey--text body-1 mb-5">
              <v-icon class="orange--text">school</v-icon>
              Pedagogy
            </h2>
            <h2 class="grey--text body-1 text-left mt-5">
              <v-icon class="orange--text mr-2">groups</v-icon>
              Your events
            </h2>
            <p class="grey--text subtitle-2 text-left mt-4">
              You haven't presented any watch so far! …and haven't participated
              in any hackathon so far! You haven't gone to any job or internship
              Interview so far.
            </p>
            <v-btn outlined class="grey--text text-capitalize mb-5">
              <v-icon left class="orange--text">add_circle_outline</v-icon>
              add an event
            </v-btn>
            <h3 class="grey--text my-5 text-left subtitle-2">
              <v-icon left class="orange--text">text_snippet</v-icon>
              Your Evaluation Reports
            </h3>
            <p class="grey--text subtitle-2 text-left">
              Evaluation Reports are issued periodically during your training.
              They summarize your progress as well as your coaches' comments and
              are shared with our partners at VDAB/FOREM/ACTIRIS. When emitted,
              they need to be carefully read and approved.
            </p>
          </v-col>
          <!-- End Second Column -->
          <!-- Start Third Column -->
          <v-col cols="12" md="4" class="text-center">
            <h2 class="grey--text body-1 mb-5">
              <v-icon left class="orange--text">volume_up</v-icon>
              Communication
            </h2>
            <v-card flat color="grey lighten-2" class="my-3 text-left">
              <p class="grey--text pa-4 subtitle-2">
                <span class="orange--text">WARNING: </span>You're below the
                average of talk from your promo. It means you should plan a talk
                as soon as you can.
              </p>
              <v-list-item>
                <v-list-item-content>
                  <v-list-item-title class="font-weight-bold grey--text"
                    >Tech Talks</v-list-item-title
                  >
                  <hr />
                  <v-list-item-title class="mt-3 grey--text"
                    >Monday 29/03/2021</v-list-item-title
                  >
                  <v-list-item-title class="my-2 grey--text"
                    >Tech Talk: No talk planned!</v-list-item-title
                  >
                  <v-list-item-title class="mt-3 grey--text"
                    >Monday 29/03/2021</v-list-item-title
                  >
                  <v-list-item-title class="my-2 grey--text"
                    >Tech Talk: No talk planned!</v-list-item-title
                  >
                </v-list-item-content>
              </v-list-item>
              <v-btn outlined class="grey--text my-3 ml-3">
                <v-icon left class="orange--text">add_circle_outline</v-icon>
                Check Tech Talks Agenda</v-btn
              >
            </v-card>

            <v-card flat color="grey lighten-2" class="my-3 text-left">
              <v-list-item>
                <v-list-item-content>
                  <v-list-item-title class="font-weight-bold grey--text">
                    <v-icon left class="orange--text">event_note</v-icon>
                    Important Dates</v-list-item-title
                  >
                  <hr />
                  <v-list-item-title class="mt-3 grey--text"
                    >Start</v-list-item-title
                  >
                  <v-list-item-title class="my-2 grey--text"
                    >30 Sep 2020</v-list-item-title
                  >
                  <v-list-item-title class="mb-2 grey--text"
                    >Holiday 1</v-list-item-title
                  >
                  <v-list-item-title class="grey--text"
                    >2 Nov 2020 to 6 Nov 2020</v-list-item-title
                  >
                  <v-list-item-title class="mb-2 grey--text"
                    >Holiday 2</v-list-item-title
                  >
                  <v-list-item-title class="grey--text"
                    >2 Nov 2020 to 6 Nov 2020</v-list-item-title
                  >
                  <v-list-item-title class="mb-2 grey--text"
                    >Internship start</v-list-item-title
                  >
                  <v-list-item-title class="grey--text"
                    >16 Apr 2021 (17 days left)</v-list-item-title
                  >
                  <v-list-item-title class="mb-2 grey--text"
                    >End</v-list-item-title
                  >
                  <v-list-item-title class="grey--text"
                    >12 Jul 2021 (104 days left)</v-list-item-title
                  >
                </v-list-item-content>
              </v-list-item>
            </v-card>
          </v-col>
          <!-- End Third Column -->
        </v-row>
      </v-card>
      <!-- End Second Card -->
    </v-container>
    <!-- End Container -->
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "dashboard",
};
</script>

<style lang="scss" scoped>
.dashboard {
  .main_info {
    .img {
      width: 60px;
      height: 60px;
      display: block;
      border: 2px solid #9e9e9e;
      border-radius: 7px;
    }
    .info_personne {
      position: relative;
      top: -64px;
      left: 87px;
      .name {
        text-transform: capitalize;
        font-weight: bold;
        font-size: 1.2em !important;
      }
    }
  }
}
</style>
