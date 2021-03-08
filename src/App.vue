<template>
  <div id="app">
    <header id="nav" class="sticky-nav">
      <nav class="w-container">
        <div class="w-row">
          <div class="w-col w-col-4 w-col-medium-4 w-col-small-4 w-col-tiny-4">
            <a href="#" class="nav-logo-link">
              <img src="./assets/images/RateGenieLogo.png" alt class="nav-logo" />
              <img src="./assets/images/icon_Rategenie.png" alt class="nav-logo moblogo" />
            </a>
          </div>
          <div class="w-col w-col-4 w-col-medium-2 w-col-small-2 w-col-tiny-2"></div>
          <div class="w-col w-col-4 w-col-medium-6 w-col-small-6 w-col-tiny-6">
            <ul role="list" class="nav-grid w-list-unstyled">
              <li></li>
              <li>
                <a href="#" class="w-button calagent">Call Agent</a>
              </li>
              <li>
                <a href="#" class="nav-link">
                  <img src="./assets/images/messenger.png" />
                </a>
              </li>
            </ul>
          </div>
        </div>
      </nav>
    </header>

    <div class="avatarsection">
      <div class="userlogo w-container">
        <div class="avatarimage">
          <img src="https://ca.slack-edge.com/T20F5T4TZ-U20EWEZF0-b8525c6e0078-512" />
        </div>
        <div class="username">John Realtor</div>
      </div>
    </div>

    <div class="section2">
      <div class="consec2 w-container">
        <h2 class="heading3">Estimated Value</h2>
        <p class="paragraph">
          This is an automated valuation based off of tax records, public data and recently sold properties.
          <br class="desktop-only" />An approved local expert will follow up with a more detailed report shortly.
        </p>
        <div class="div-block">
          <div class="price1">
            <div class="symbol1">$</div>
            <h1 class="heading-2">675,000</h1>
          </div>

          <div class="text-block">Average home value with 4 valuations</div>
        </div>
        <div class="div-block-2 desktop-only">
          <a href="#" class="pbbk w-button blacknightbuton">
            <img src="./assets/images/icon_BlackKnight.png" />
            <span>PROVIDED BY BLACK KNIGHT</span>
          </a>
        </div>
      </div>
    </div>
    <div class="section valuationsection">
      <div class="container w-container">
        <div class="valuationblock blackknightblock">
          <div class="w-row">
            <div class="w-col w-col-4 w-col-medium-4 w-col-small-4 w-col-tiny-4">
              <div class="valueamount">
                <div class="symbol">$</div>
                <h1 class="heading200">200,000</h1>
              </div>
              <div class="text-block-2">LOW ESTIMATE</div>
            </div>
            <div class="w-col w-col-4 w-col-medium-4 w-col-small-4 w-col-tiny-4 black">
              <div class="valueamount">
                <div class="symbol">$</div>
                <h1 class="heading200">260,000</h1>
              </div>
              <div class="text-block-2">MEDIAN ESTIMATE</div>
            </div>
            <div class="w-col w-col-4 w-col-medium-4 w-col-small-4 w-col-tiny-4">
              <div class="valueamount">
                <div class="symbol">$</div>
                <h1 class="heading200">300,000</h1>
              </div>
              <div class="text-block-2">HIGH ESTIMATE</div>
            </div>
          </div>
          <div class="div-block-2 mobile-only">
            <a href="#" class="pbbk w-button blacknightbuton">
              <img src="./assets/images/icon_BlackKnight.png" />
              <span>PROVIDED BY BLACK KNIGHT</span>
            </a>
          </div>
        </div>

        <div class="div-block-3 desktop-only">
          <img src="./assets/images/graph.png" />
        </div>

        <div class="valuationblock firstamerican">
          <div class="w-row">
            <div class="w-col w-col-4 w-col-medium-4 w-col-small-4 w-col-tiny-4">
              <div class="valueamount">
                <div class="symbol">$</div>
                <h1 class="heading200">200,000</h1>
              </div>
              <div class="text-block-2">LOW ESTIMATE</div>
            </div>
            <div class="w-col w-col-4 black w-col-medium-4 w-col-small-4 w-col-tiny-4">
              <div class="valueamount">
                <div class="symbol">$</div>
                <h1 class="heading200">260,000</h1>
              </div>
              <div class="text-block-2">MEDIAN ESTIMATE</div>
            </div>
            <div class="w-col w-col-4 w-col-medium-4 w-col-small-4 w-col-tiny-4">
              <div class="valueamount">
                <div class="symbol">$</div>
                <h1 class="heading200">300,000</h1>
              </div>
              <div class="text-block-2">HIGH ESTIMATE</div>
            </div>
          </div>
        </div>

        <div class="div-block-4">
          <a href="#" class="pbbk w-button famericanbuton">
            <img src="./assets/images/icon_Firstam.png" />
            <span>PROVIDED BY First American</span>
          </a>
        </div>

        <div class="_2partcol">
          <div class="w-row">
            <div class="doulecols w-col w-col-6 zillowblock">
              <a href="#" class="pbbk w-button desktop-only zillowbuton">
                <img src="./assets/images/icon_Zillow.png" />
                <span>PROVIDED BY Zillow</span>
              </a>

              <div class="columnshalf w-row">
                <div class="w-col w-col-4 w-col-medium-4 w-col-small-4 w-col-tiny-4">
                  <div class="valueamount">
                    <div class="symbol">$</div>
                    <h1 class="heading200">200,000</h1>
                  </div>
                  <div class="text-block-2">LOW ESTIMATE</div>
                </div>
                <div class="w-col w-col-4 black bborder w-col-medium-4 w-col-small-4 w-col-tiny-4">
                  <div class="valueamount">
                    <div class="symbol">$</div>
                    <h1 class="heading200">260,000</h1>
                  </div>
                  <div class="text-block-2">MEDIAN ESTIMATE</div>
                </div>
                <div class="w-col w-col-4 w-col-medium-4 w-col-small-4 w-col-tiny-4">
                  <div class="valueamount">
                    <div class="symbol">$</div>
                    <h1 class="heading200">300,000</h1>
                  </div>
                  <div class="text-block-2">HIGH ESTIMATE</div>
                </div>
              </div>
            </div>
            <div class="doulecols w-col w-col-6 remineblock">
              <div>
                <div>
                  <div>
                    <a href="#" class="pbbk w-button desktop-only reminbutton">
                      <img src="./assets/images/icon_Remine.png" />
                      <span>PROVIDED BY Remine</span>
                    </a>

                    <div class="columnshalf w-row">
                      <div class="w-col w-col-4 w-col-medium-4 w-col-small-4 w-col-tiny-4">
                        <div class="valueamount">
                          <div class="symbol">$</div>
                          <h1 class="heading200">200,000</h1>
                        </div>
                        <div class="text-block-2">LOW ESTIMATE</div>
                      </div>
                      <div
                        class="w-col w-col-4 black bborder w-col-medium-4 w-col-small-4 w-col-tiny-4"
                      >
                        <div class="valueamount">
                          <div class="symbol">$</div>
                          <h1 class="heading200">260,000</h1>
                        </div>
                        <div class="text-block-2">MEDIAN ESTIMATE</div>
                      </div>
                      <div class="w-col w-col-4 w-col-medium-4 w-col-small-4 w-col-tiny-4">
                        <div class="valueamount">
                          <div class="symbol">$</div>
                          <h1 class="heading200">300,000</h1>
                        </div>
                        <div class="text-block-2">HIGH ESTIMATE</div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="valuationblock">
        <div class="singleborder"></div>
      </div>
    </div>

    <div class="section-2">
      <div class="container-2 w-container">
        <div>
          <h2 class="heading3">Estimated Value</h2>
          <p class="paragraph">
            This is an automated valuation based off of tax records, public data and recently sold properties.
            <br class="desktop-only" />An approved local expert will follow up with a more detailed report shortly.
          </p>
        </div>

        <div class="tablesection">
          <div class="w-row">
            <div class="w-col w-col-6">
              <box-statistics-30 />
            </div>

            <div class="w-col w-col-6">
              <box-statistics-15 />
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="lgyul">
      <div class="container-3 w-container cenimagecontainer">
        <div class="cenimage">
          <img src="https://ca.slack-edge.com/T20F5T4TZ-U20EWEZF0-b8525c6e0078-512" />
        </div>
      </div>
    </div>

    <div class="lgyul">
      <div class="container-3 w-container">
        <div>
          <h1 class="heading-18">Let’s Get You Locked Into A Low Rate!</h1>
          <div class="text-block-17">
            All we need is 15 minutes to layout
            <br class="mobile-only" />all of your refinancing options.
          </div>
        </div>
        <div class="div-block-11">
          <a href="#" class="lympo w-button">Lower Your Mortgage Payment</a>
        </div>
        <div class="div-block-12">
          <img src="./assets/images/logo_axos.png" loading="lazy" width="73" alt class="image" />
          <img src="./assets/images/logo_caliber.png" loading="lazy" width="120" alt class="image" />
          <img src="./assets/images/logo_NewRez.jpg" loading="lazy" width="122" alt class="image" />
          <img src="./assets/images/logo_Plaza.jpeg" loading="lazy" width="132" alt class="image" />
          <img src="./assets/images/logo_Sprout.png" loading="lazy" width="182" alt class="image" />
          <img src="./assets/images/logo_UWM.png" loading="lazy" width="75" alt class="image" />
        </div>

        <div class="divider"></div>
      </div>
    </div>
    <property />
    <div class="sectionlast">
      <div class="w-container">
        <h1 class="heading-19">Similar Property</h1>
        <div class="mapdiv">
          <div class="text-block-27">
            <img src="./assets/images/map2.png" />
          </div>
          <div class="tablediv">
            <table>
              <thead>
                <tr>
                  <th>Address</th>
                  <th>Sold Price</th>
                  <th>Sold Date</th>
                  <th>Est. Value</th>
                  <th>Price Diff.</th>
                  <th>Square Feet</th>
                  <th>$/Sq Foot</th>
                </tr>
              </thead>
              <tbody>
                <tr v-for="(property, i) in similarProperties" :key="i">
                  <td data-label="address">
                    <div class="tableaddr">
                      <div class="imag">
                        <img :src="`${property.image}`" />
                      </div>
                      <div class="details">
                        {{property.address.firstAddress}}
                        <br />
                        <strong>{{property.address.lastAddress}}</strong>
                      </div>
                    </div>
                  </td>
                  <td data-label="sprice">{{property.soldPrice}}</td>
                  <td data-label="sdate">{{property.soldDate}}</td>
                  <td data-label="estvalue">{{property.estimatedValue}}</td>
                  <td data-label="pdiff" class="pdif">{{property.priceDifference}}</td>
                  <td data-label="sqft">{{property.squareFeet}}</td>
                  <td data-label="sqfot">{{property.pricePerFoot}}</td>
                </tr>
              </tbody>
            </table>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import BoxStatistics30 from "./components/refinance/BoxStatistics30.vue";
import BoxStatistics15 from "./components/refinance/BoxStatistics15.vue";
import Property from "./components/refinance/Property.vue";
export default {
  name: "App",
  components: {
    BoxStatistics30,
    BoxStatistics15,
    Property
  },
  data() {
    return {
      similarProperties: [
        {
          image: "http://ivyleadserver.com/rhomevalu/images/color.png",
          address: {
            firstAddress: "6969 HARDWOOD LN.",
            lastAddress: "LOS ANGELES, CA."
          },
          soldPrice: "$ 000,000",
          soldDate: "01 / 01 / 21",
          estimatedValue: "$ 000,000",
          priceDifference: "0,0 %",
          squareFeet: "0,000",
          pricePerFoot: "$ 000"
        },
        {
          image: "http://ivyleadserver.com/rhomevalu/images/color.png",
          address: {
            firstAddress: "6969 HARDWOOD LN.",
            lastAddress: "LOS ANGELES, CA."
          },
          soldPrice: "$ 000,000",
          soldDate: "01 / 01 / 21",
          estimatedValue: "$ 000,000",
          priceDifference: "0,0 %",
          squareFeet: "0,000",
          pricePerFoot: "$ 000"
        },
        {
          image: "http://ivyleadserver.com/rhomevalu/images/color.png",
          address: {
            firstAddress: "6969 HARDWOOD LN.",
            lastAddress: "LOS ANGELES, CA."
          },
          soldPrice: "$ 000,000",
          soldDate: "01 / 01 / 21",
          estimatedValue: "$ 000,000",
          priceDifference: "0,0 %",
          squareFeet: "0,000",
          pricePerFoot: "$ 000"
        },
        {
          image: "http://ivyleadserver.com/rhomevalu/images/color.png",
          address: {
            firstAddress: "6969 HARDWOOD LN.",
            lastAddress: "LOS ANGELES, CA."
          },
          soldPrice: "$ 000,000",
          soldDate: "01 / 01 / 21",
          estimatedValue: "$ 000,000",
          priceDifference: "0,0 %",
          squareFeet: "0,000",
          pricePerFoot: "$ 000"
        }
      ]
    };
  }
};
</script>

<style scoped>
@import "./css/normalize.css";
@import "./css/refihomevaluation-jannat.webflow.css";
@import "./css/webflow.css";

.calagent {
  background: #02c667;
  line-height: 34px;
  padding: 0 10px;
  font-weight: 400;
}

.pbbk {
  border-style: solid;
  border-width: 1px;
  border-color: #999;
  background-color: transparent;
  color: #999;
  text-transform: uppercase;
  padding: 5px 15px 5px;
  line-height: 30px;
}

.lympo {
  margin-bottom: 0px;
  padding: 0px 30px;
  background-color: #02c667;
  font-size: 16px;
  line-height: 47px;
  font-weight: 700;
}
</style>
