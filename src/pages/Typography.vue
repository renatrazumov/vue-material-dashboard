<template>
  <div class="content">
    <div class="md-layout">
      <div class="md-layout-item">
        <md-card>
          <md-card-header data-background-color="green">
            <h4 class="title">Electric Vehicle Experience Score</h4>
            <p class="category">Created using Transportation Protcol</p>
          </md-card-header>
          <md-card-content>
            <div id="typography">
              <div class="title">
                <h2>EVXS - Transportation Protocol</h2>
              </div>
              <div class="row">
                <div class="body">
                  <p>
                    <h3><span class="body">What is the EVXS - Transportation Protocol?</span></h3>
                    - Dynamically calculate the best electric charging station from current location.
                    - Display maps view, including map markers overlays with 10 km radius.
                  </p>
                </div>
                <div class="body">
                  <p>
                    <h3><span class="body">How does the EVXS - Transportation Protocol work?</span></h3>
                    - EVXS provides a system of scoring search results from HERE location services based upon the following
                  </p>
                </div>
                <div class="body">
                  <span class="body"></span>
                    <p>- Search results sorted by distance proximity from current location to routed locations</p>
                    <p>- Result returns list of electric charging stations by order of proximity to current location</p>
                    <p>- Generate route between two locations and plotting coordinate markers on the map from current location within 10km.</p>
                    <p>- Parse JSON request from HERE Places API by proximity, from current location.</p>
                    <p>- Parse data from IoT enabled vehicles to get battery life percentage.</p>
                    <p>- Display maps view, including map markers overlays with 10 km radius.</p>
                </div>
                <div class="body">
                  <p>
                    <h3><span class="body">The Problem: “Range Anxiety” “Time Saved” “Reduced Carbon Footprint”</span></h3>
                    - Focus: In-Car Experience, Holistic Efficiency, Retail, Driver Time Saved
                  </p>
                </div>
                <div class="body">
                  <span class="body"></span>
                    <p>- For each hour of charging current EVs get approx 20-30 miles of range.</p>
                    <p>- Battery Range, Fuel Costs / Charge Cost, Duration of Charge Time.</p>
                    <p>- Routing your journey is key to enjoying the EV experience.</p>
                    <p>- EV Charging may take many hours - long distance trips require multiple charges.</p>
                </div>
                <div class="body">
                  <p>
                    <h3><span class="body">Our Solution: EVX SCORE</span></h3>
                    <p>- Select the best route to the EV Charger - charging takes hours - plan accordingly with EVX score.
                    <p>- Scenario: EV operator is traveling I-5 “Electric Highway” for an 1,121 Mile Trip from LA to Portland.
                    <p>- “Alexa - What is the most efficient place (EVX score) to charge & park”
                    <p>- “Alexa - Show me a map of EV Chargers within a 10 km radius”
                    <p>- EVX Score is based on the following criteria:
                    <p>- Distance from location to routed destination
                    <p>- Distance from charger to charger
                  </p>
                </div>
              </div>
            </div>
          </md-card-content>
        </md-card>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    dataBackgroundColor: {
      type: String,
      default: ""
    }
  }
};
</script>
