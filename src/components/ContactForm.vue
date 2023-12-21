<template>
    <v-container>
      <v-col cols="12" sm="12" class="px-16" id="contact">
        <v-row>
          <v-col cols="12" sm="4">
            <div class="child">
              <h1>Contact info</h1>
              <v-icon
                size="40"
                variant="outlined"
                class="mt-10 mdi mdi-checkbox-multiple-marked-circle"
              ></v-icon>
              <br />
              <span class="text-caption"> Street 27A, Exeter, England </span
              ><br />
              <v-btn icon="fas fa-chevron-down" color="" class="mt-10" variant=""
                ><v-icon size="34" class="mdi mdi-phone-classic"> </v-icon></v-btn
              ><br />
              <span class="text-caption">01235 - 6521 </span> <br />
              <span class="text-caption">01235 - 6521 </span> <br />
              <v-btn
                icon="fas fa-envelope"
                color=""
                class="mt-10"
                variant="outlined"
                ><v-icon size="35" class="mdi mdi-email-open"> </v-icon></v-btn
              ><br />
              <span class="text-caption">wedaydresses@gmail.com </span> <br />
              <span class="text-caption">managementwedaydresses@gmail.com </span> <br />
            </div>
          </v-col>
          <v-col cols="12" sm="8">
            <h1 class="mt-8">Send your message</h1>
            <v-divider></v-divider>
            <span class="text-caption"
              >We are open from Monday to Friday. Please do not hesitate to
              contact us and ask questions.
            </span>
            <v-row class="mt-10">
              <v-col cols="12" sm="6">
                <v-text-field
                  label="Name"
                  persistent-hint
                  variant="outlined"
                ></v-text-field>
              </v-col>
              <v-col cols="12" sm="6">
                <v-text-field
                  label="Phone No"
                  persistent-hint
                  variant="outlined"
                ></v-text-field>
              </v-col>
            </v-row>
            <v-textarea
              label="Message"
              persistent-hint
              variant="outlined"
            ></v-textarea>
            <!-- <v-btn color="#FBDF7E" class="mt-2">Submit Now</v-btn> -->
            <v-btn
              rounded
              flat
              medium
              class="py-5 p-2 d-none d-sm-none d-md-flex grey darken-1 white--text"
            >
              Submit Now
            </v-btn>
          </v-col>
        </v-row>
      </v-col>
    </v-container>
  </template>
  <style>
  .v-container {
    padding: 16px 0 16px 0;
  }
  
  .first {
    width: 100%;
    height: 280px;
    text-align: center;
    padding: 2rem 2rem;
  }
  .child {
    display: inline-block;
    padding: 2rem 1rem;
    vertical-align: middle;
    text-align: center;
    margin-right: 8px;
  }
  
  .pre {
    width: 100%;
    height: 380px;
    text-align: center;
    padding: 0 200px;
    background-color: #f5f5f5;
  }
  </style>
  <script>
  export default{}
  </script>
  