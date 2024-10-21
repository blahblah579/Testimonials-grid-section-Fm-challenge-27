<template>
  <v-container fluid class="body px-0 px-md-13 my-10">
    <v-row class="px-lg-7">
      <v-col cols="12" class="d-flex flex-wrap body px-0 px-md-14">
        <v-col cols="12" md="9" class="d-flex flex-wrap left">
          <v-col cols="12" sm="8" class="">
            <v-col cols="12" class="one d-flex flex-column pl-6 pr-10 py-7">
              <div class="profile d-flex">
                <v-avatar size="26">
                  <v-img
                    class="dp1"
                    alt="John"
                    src="/src/assets/image-daniel.jpg"
                  ></v-img>
                </v-avatar>
                <div class="details">
                  <div class="name1">Daniel Clifford</div>
                  <div class="designation1">Verified Graduate</div>
                </div>
              </div>

              <div class="heading1">
                I received a job offer mid- course, and the subjects learned
                were current, if not more so, in the company I joined. I
                honestly feel I got every penny's worth.
              </div>
              <v-spacer></v-spacer>
              <div class="subheading1 mt-3">
                "I was an EMT for many years before I joined the bootcamp. I've
                been looking to make a transition and have heard some people who
                had an amazing experience here. I signed up for the free intro
                course and found it incredibly fun! I enrolled shortly
                thereafter. The next 12 weeks was the best-and most grueling -
                time of my life. Since completing the course, I've successfully
                switched careers, working as a Software Engineer at a VR
                startup."
              </div>
            </v-col>
          </v-col>
          <v-col cols="12" sm="4">
            <v-col cols="12" class="two d-flex flex-column px-6 py-7">
              <div class="profile d-flex">
                <v-avatar size="26">
                  <v-img
                    class="dp2"
                    alt="John"
                    src="/src/assets/image-jonathan.jpg"
                  ></v-img>
                </v-avatar>
                <div class="details">
                  <div class="name2">Jonathan Walters</div>
                  <div class="designation2">Verified Graduate</div>
                </div>
              </div>

              <div class="heading2">
                The team was very supportive and kept me motivated
              </div>
              <v-spacer></v-spacer>
              <div class="subheading2">
                "I started as a total newbie with virtually no coding skills. I
                now work as a mobile engineer for a big company. This was one of
                the best investments I've made in myself."
              </div>
            </v-col>
          </v-col>
          <v-col cols="12" sm="4">
            <v-col cols="12" class="three d-flex flex-column px-6 py-7">
              <div class="profile d-flex">
                <v-avatar size="26">
                  <v-img
                    class="dp3"
                    alt="John"
                    src="/src/assets/image-jeanette.jpg"
                  ></v-img>
                </v-avatar>
                <div class="details">
                  <div class="name3">Jeanette Harmon</div>
                  <div class="designation3">Verified Graduate</div>
                </div>
              </div>

              <div class="heading3">
                An overall wonderful and rewarding experience
              </div>
              <v-spacer></v-spacer>
              <div class="subheading3">
                "Thank you for the wonderful experience! I now have a job I
                really enjoy, and make a good living while doing something I
                love."
              </div>
            </v-col>
          </v-col>
          <v-col cols="12" sm="8">
            <v-col cols="12" class="four d-flex flex-column px-6 py-7">
              <div class="profile d-flex">
                <v-avatar size="26">
                  <v-img
                    class="dp4"
                    alt="John"
                    src="/src/assets/image-patrick.jpg"
                  ></v-img>
                </v-avatar>
                <div class="details">
                  <div class="name4">Patrick Abrams</div>
                  <div class="designation4">Verified Graduate</div>
                </div>
              </div>

              <div class="heading4">
                Awesome teaching support from TAs who did the bootcamp
                themselves. Getting guidance from them and learning from their
                experiences was easy.
              </div>
              <v-spacer></v-spacer>
              <div class="subheading4">
                "The staff seem genuinely concerned about my progress which I
                find really refreshing. The program gave me the confidence
                necessary to be able to go out in the world and present myself
                as a capable junior developer. The standard is above the rest.
                You will get the personal attention you need from an incredible
                community of smart and amazing people."
              </div>
            </v-col>
          </v-col>
        </v-col>
        <v-col cols="12" md="3" class="right pl-md-0 pt-0 pt-md-3">
          <v-col class="pl-md-0 right1 pt-0 pt-md-3">
            <v-col cols="12" class="five d-flex flex-column px-6 py-7">
              <div class="profile d-flex">
                <v-avatar size="26">
                  <v-img
                    class="dp5"
                    alt="John"
                    src="/src/assets/image-kira.jpg"
                  ></v-img>
                </v-avatar>
                <div class="details">
                  <div class="name5">Kira Whittle</div>
                  <div class="designation5">Verified Graduate</div>
                </div>
              </div>

              <div class="heading5">
                Such a life-changing experience. Highly recommended!
              </div>
              <div class="subheading5 mt-5">
                "Before joining the bootcamp, I've never written a line of code.
                I needed some structure from professionals who can help me learn
                programming step by step. I was encouraged to enroll by a former
                student of theirs who can only say wonderful things about the
                program. The entire curriculum and staff did not disappoint.
                They were very hands-on and I never had to wait long for
                assistance. The agile team project, in particular, was
                outstanding. It took my learning to the next level in a way that
                no tutorial could ever have. In fact, I've often referred to it
                during interviews as an example of my developent experience. It
                certainly helped me land a job as a full-stack developer after
                receiving multiple offers. 100% recommend!"
              </div>
            </v-col>
          </v-col>
        </v-col>
      </v-col>
    </v-row>
  </v-container>
</template>


<style scoped>
@font-face {
  font-family: f1;
  src: url(/src/assets/BarlowSemiCondensed-Medium.ttf);
}
@font-face {
  font-family: f2;
  src: url(/src/assets/BarlowSemiCondensed-Bold.ttf);
}
@font-face {
  font-family: f3;
  src: url(/src/assets/BarlowSemiCondensed-Regular.ttf);
}
@font-face {
  font-family: f4;
  src: url(/src/assets/BarlowSemiCondensed-SemiBold.ttf);
}
.body {
  padding: 0 51.7px 0 51.7px;
}
.one {
  background-color: #733fc8;
  border-radius: 10px;
  height: 100%;
  /* Background image properties */
  background-image: url("/src/assets/bg-pattern-quotation.svg");
  background-size: initial; /* Ensures the image fits inside the container */
  background-repeat: no-repeat; /* Prevents repeating the image */
  background-position: 280px 0px; /* Default position at center */
  box-shadow: 0px 14px 16px rgba(0, 0, 0, 0.1); /* Adds a light shadow */
}

.dp1 {
  border: 2px solid hsl(264, 83%, 70%);
  border-radius: 50%;
}
.heading1,
.heading2,
.heading4,
.heading3,
.heading5 {
  font-size: 16px;
  font-family: f4;
  letter-spacing: 1px;
}
.heading1,
.heading2,
.heading4 {
  margin-top: 13px;
  z-index: 1;
  line-height: 20px;
}
.subheading1 {
  font-size: 11.5px;
  color: hsl(264, 73%, 75%);
  font-family: f3;
  font-weight: bold;
}
.name1,
.name2,
.name4 {
  font-family: f1;
  font-size: 10px;
  position: relative;
  top: 1px;
}
.designation1 {
  font-size: 10px;
  color: hsl(264, 83%, 70%);
  font-family: f1;
  position: relative;
  top: -1px;
}

.two {
  background-color: hsl(219, 19%, 35%);
  border-radius: 10px;
  height: 100%;
  box-shadow: 0px 14px 16px rgba(0, 0, 0, 0.1); /* Adds a light shadow */
}
.designation2,
.designation4 {
  font-size: 10px;
  color: hsl(224, 9%, 68%);
  font-family: f1;
}
.subheading2,
.subheading4 {
  font-size: 12px;
  font-family: f3;
  color: hsl(224, 9%, 68%);
  font-weight: bold;
}

.three,
.five {
  background-color: hsl(0, 0%, 100%);
  border-radius: 10px;
  height: 100%;
}

.name3,
.name5 {
  font-family: f1;
  font-size: 10px;
  color: hsl(217, 19%, 35%);
  position: relative;
  top: 1px;
}
.designation3,
.designation5 {
  font-size: 10px;
  color: hsl(228, 4%, 77%);
  font-family: f1;
  position: relative;
  top: -1px;
}
.heading3,
.heading5 {
  line-height: 20px;
  margin-top: 12px;
  color: hsl(217, 19%, 35%);
}
.subheading3,
.subheading5 {
  font-size: 12px;
  font-family: f3;
  font-weight: bold;
  color: hsl(228, 3%, 63%);
}
.three {
  box-shadow: 0px 14px 16px rgba(0, 0, 0, 0.1); /* Adds a light shadow */
}
.four {
  background-color: hsl(217, 30%, 14%);
  border-radius: 10px;
  height: 100%;
  box-shadow: 0px 14px 16px rgba(0, 0, 0, 0.1); /* Adds a light shadow */
}
.dp4 {
  border: 2px solid hsl(264, 83%, 70%);
  border-radius: 50%;
}
.five {
  height: 100%;
  background-color: #fff;
  box-shadow: 0px 14px 16px rgba(0, 0, 0, 0.1); /* Adds a light shadow */
}
.details {
  margin-left: 15px;
  padding: 0px;
  display: flex;
  flex-direction: column;
  justify-content: center;
}
.right1 {
  height: 100%;
}
</style>