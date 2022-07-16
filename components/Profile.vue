<template>
  <v-list-item class="mx-auto">
    <v-row justify="center">
      <v-col sm="10" md="6" lg="4">
        <v-card
          class="text-left mx-auto"
          max-width="500"
          height="500"
          outlined
          style=""
        >
          <v-list-item three-line>
            <v-list-item-content>
              <div class="text-overline h4 mb-4">
                <h4>About Me</h4>
              </div>
              <v-list-item-title class="text-h5 mb-1">
                Watthanatham Kruram
              </v-list-item-title>
              <v-list-item-title class="text-h5 mb-1">
                (Watt)
              </v-list-item-title>
              <v-list-item-subtitle class="mb-1">Born: 17/ 11 /1999</v-list-item-subtitle>
              <br />
              <v-list-item-subtitle class="mb-1">Nationality: Thai</v-list-item-subtitle>
            </v-list-item-content>

            <v-avatar size="120">
              <v-img :src="require('../assets/images/student_ham.jpg')"></v-img>
            </v-avatar>
          </v-list-item>
        </v-card>
      </v-col>
      <v-col sm="10" md="6" lg="4">
        <v-card class="text-left mx-auto" max-width="500" height="500" outlined>
          <v-list-item three-line>
            <v-list-item-content>
              <div class="text-overline h4 mb-4">
                <h4>Education</h4>
              </div>
              <v-list-item-title class="text-h5 mb-1">
                Watthanatham Kruram
              </v-list-item-title>
              <v-list-item-subtitle>Born: 17/11/1999</v-list-item-subtitle>
              <br />
              <v-list-item-subtitle></v-list-item-subtitle>
            </v-list-item-content>

            <v-avatar size="120" class="ml-10">
              <v-img :src="require('../assets/images/student_ham.jpg')"></v-img>
            </v-avatar>
          </v-list-item>
        </v-card>
      </v-col>
      <v-col sm="10" md="6" lg="4">
        <v-card class="text-left mx-auto" max-width="500" height="500" outlined>
          <v-list-item three-line>
            <v-list-item-content>
              <div class="text-overline h4 mb-4">
                <h4>Skills</h4>
              </div>
              <v-list-item-title class="text-h5 mb-1">
                Watthanatham Kruram
              </v-list-item-title>
              <v-list-item-subtitle
                >I want to be Programmer.</v-list-item-subtitle
              >
              <br />
              <v-list-item-subtitle>Hello</v-list-item-subtitle>
            </v-list-item-content>

            <v-avatar size="120">
              <v-img :src="require('../assets/images/student_ham.jpg')"></v-img>
            </v-avatar>
          </v-list-item>
        </v-card>
      </v-col>
    </v-row>
  </v-list-item>
</template>