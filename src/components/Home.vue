<template>
   <div class="content" style="overflow-x: hidden;" @scroll="asd()">
      <navbar/>
      <div class="container position-relative hero">
         <div class="row d-flex align-items-center justify-content-between py-5 my-5 position-relative hero-content">
            <div class="col-12 col-sm-12 col-md-6 " style="text-align: -webkit-left;">
               <h1 class="h2" hidden>Babythundercake</h1>
               <!-- <img width="350" class="d-block mb-3" src="assets/img/SVG/Logotype.svg" alt="BabyPoo"> -->
               <h5 class="mb-2 mr-3">Buy, hold, and be rewarded with Thundercake and Cake which will automatically be credited on your wallet for every transaction you make!</h5>
               <div class="d-flex align-items-center mb-2 ">
               </div>
               <p>
                  What if Cake and Thundercake had a crazy night?
               </p>
               <p class="">
                  $BabyThunderCake is the great innovation of ThunderCake that will amazingly feed your family through $Cake. Its father, ThunderCake continues to give you Thundercake and Cake while holding them!
                  The automatic claim function of $BabyThunderCake will spontaneously send you ThunderCake and Cake.
                  ThunderCake and Cake rewards that $BabyThunderCake offers is so awesome that it gives SUGAR RUSH to your wallet!
               </p>
               <div class="">
                  <a class="btn btn-primary text-white m-1" target="_blank" href="https://pancakeswap.finance/swap?outputCurrency=0xf1496dc3054b99bfe48b6738320d45eef8513610">
                  <img width="30" class="mr-2" src="@/assets/images/LogoPancake.png" alt="">
                  Buy now!
                  </a>
                  <a class="btn btn-primary text-white m-1" target="_blank" href="https://www.dextools.io/app/pancakeswap/pair-explorer/0x946c1354e5f0ad36b067dd3b4f772de10a34ba36">
                  <img width="30" class="mr-2" src="@/assets/images/dextools.png" alt="">
                  Dextools
                  </a>
                  <a class="btn btn-primary text-white btn-small m-1" target="_blank" href="https://poocoin.app/tokens/0xf1496dc3054b99bfe48b6738320d45eef8513610">
                  <img width="30" class="mr-2" src="@/assets/images/poocoin.png" alt="">
                  Poo Chart
                  </a>
               </div>
            </div>
            <div class="col-12 col-sm-12 col-md-6 d-flex position-relative justify-content-center">
               <img class="character d-block mt-auto" src="@/assets/images/babythundercake.gif" alt="Babythundercake">
            </div>
         </div>
      </div>
      <div class="w-100 d-blok position-relative mt-4">
         <div class="w-100 position-absolute " style="left: 0; bottom: -1px; right: 0; overflow: hidden;">
            <svg style="width: 100%; height: auto; display: block; transform: scale(2); transform-origin: top center"
               viewBox="0 0 2880 48" fill="#d08750" xmlns="http://www.w3.org/2000/svg">
               <path d="M0 48h2880V0h-720C1442.5 52 720 0 720 0H0v48z" fill="#d08750"></path>
            </svg>
         </div>
      </div>
      <div id="why" class="bg-dark text-white khaki">
         <div class="container text-center pb-3 position-relative">
            <div class="row pt-5">
               <div class="container">
                  <div class="text-center">
                     <h3 class="violet" style="font-size: 175%">Why we created $BabyThunderCake?</h3>
                     <p>We have seen people enjoying and adapting rewards system like $Cake and $Thundercake.</p>
                  </div>
               </div>
            </div>
            <div class="row align-items-center py-5">
               <div class="col-12 col-sm-6 col-md-6">
                  <img class="d-block mt-auto" src="@/assets/images/teeter.gif" style="width: 100%" alt="Babythundercake">
               </div>
               <div class="col-12 col-sm-6 col-md-6 text-left">
                  <h4>So, the 1 Billion MarketCap question was...</h4>
                  <h6 class="mb-4">
                     “What could be the next altcoin token that will be a great trending and make people filthy rich?” 
                  </h6>
                  <p>
                     With this question, we have formulated a contract of what we think is the best for our investors.
                     We came up with the best answer and SUGAR RUSH from $CAKE REWARDS won’t make you fat, but your POCKET surely will!
                  </p>
                  <p>
                     It’s like hitting two birds with one stone! Having $Cake rewards mixed with the Thunder God of Crypto,
                     THUNDERCAKE will absolutely be a DIABETIC SHOCK for everyone!
                  </p>
                  <h5 class="violet">Get both rewards at the same time!</h5>
               </div>
            </div>
         </div>
      </div>
      <div id="features" class="w-100">
         <div class="row align-items-start">
            <div class="col-12 col-md-12 py-5 bg-white">
               <div class="pb-3" style="text-align: center;">
                  <small class="text-secondary">Great Features:</small>
                  <h3 class="violet">Tokenomics</h3>
               </div>
               <div class="row" style="justify-content: center;">
                  <div class="col-12 col-md-8 col-sm-12 row justify-content-center tokenomic-cards">
                     <div class="d-flex pb-2 col-md-5">
                        <div>
                           <font-awesome-icon icon="question-circle" class="fa-2x mb-3 mr-3"/>
                           <h6>How the contract works</h6>
                        </div>
                        <p>Poocoin chart will show 5 transactions for every sale that occurs:</p>
                        <ul>
                           <font-awesome-icon icon="bolt" class="text-success mr-2"/>
                           <small>Seller’s transaction</small>
                        </ul>
                        <ul>
                           <font-awesome-icon icon="bolt" class="text-success mr-2"/>
                           <small>4% Cake rewards</small>
                        </ul>
                        <ul>
                           <font-awesome-icon icon="bolt" class="text-success mr-2"/>
                           <small>4% ThunderCake rewards</small>
                        </ul>
                        <ul>
                           <font-awesome-icon icon="bolt" class="text-success mr-2"/>
                           <small>3% Liquidity</small>
                        </ul>
                        <ul>
                           <font-awesome-icon icon="bolt" class="text-success mr-2"/>
                           <small>3% Marketing (to bring influencers on board)</small>
                        </ul>
                        <ul>
                           <font-awesome-icon icon="bolt" class="text-success mr-2"/>
                           <small>1% Sell Fee</small>
                        </ul>
                        <p>On the other hand, Dextools chart will only show a single transaction.</p>
                     </div>
                     <div class="d-flex pb-2 col-md-5">
                        <div>
                           <font-awesome-icon icon="users" class="fa-2x mb-3 mr-3"/>
                           <h6>Distribution of Cake and Thundercake</h6>
                        </div>
                        <p>
                           8% of every purchase / sale is distributed among all holders with at least 200,000 BabyThunderCake tokens.
                        </p>
                        <p>
                           The rewards will be equally divided between Cake and Thundercake
                        </p>
                     </div>
                     <div class="d-flex pb-2 col-md-5">
                        <div>
                           <font-awesome-icon icon="gem" class="fa-2x mb-3 mr-3"/>
                           <h6>Crediting of rewards</h6>
                        </div>
                        <p>
                           The rewards autosystem is activated by volume every hour wherein Thundercake and Cake will automatically reach the investors’ wallets.
                        </p>
                        <p>
                           In case of low-volume transactions, rewards crediting will then be done after an acceptable accumulated transactions to avoid gas fees.
                        </p>
                     </div>
                     <div class="d-flex pb-2 col-md-5">
                        <div>
                           <font-awesome-icon icon="lock" class="fa-2x mb-3 mr-3"/>
                           <h6>Anti-Rug System - Secured by Design</h6>
                        </div>
                        <p>
                           Initial Liquidity Provided will be locked
                        </p>
                        <p>
                           Renounced Ownership
                        </p>
                        <p>
                           5% goes to Marketing Wallet intended for massive marketing plans for Thundercake and Cake
                        </p>
                     </div>
                  </div>
                  <div class="col-12 col-md-4 col-sm-12 row justify-content-center">
                     <div class="distribution-card col">
                        <h3 class="violet">Token distribution</h3>
                        <div class="distribution-container">
                           <div class="distributed">
                              <h5>Total Supply: 100,000,000,000</h5>
                              <div class="percentage-container">
                                 <div class="bar" style="background-color: #ad500c; width: 100%;">
                                 </div>
                              </div>
                           </div>
                           <div class="distributed">
                              <h5>Pancake: 65%</h5>
                              <div class="percentage-container">
                                 <div class="bar" style="background-color: #ad500c; width: 65%;">
                                 </div>
                              </div>
                           </div>
                           <div class="distributed">
                              <h5>NFT Development Wallet: 10%</h5>
                              <div class="percentage-container">
                                 <div class="bar" style="background-color: #ad500c; width: 10%;">
                                 </div>
                              </div>
                           </div>
                           <div class="distributed">
                              <h5>Marketing: 5%</h5>
                              <div class="percentage-container">
                                 <div class="bar" style="background-color: #ad500c; width: 5%;">
                                 </div>
                              </div>
                           </div>
                        </div>
                        <div style="display: flex; flex-direction: column;">
                           <small class="text-secondary">NFT Development Wallet: 10% - LOCKED BEFORE LAUNCH</small>
                           <small class="text-secondary">Burn after 2 weeks: 20% - LOCKED BEFORE LAUNCH</small>
                        </div>
                     </div>
                  </div>
               </div>
            </div>
            <div class="w-100 d-blok position-relative">
               <div class="w-100 position-absolute " style="left: 0; bottom: -1px; right: 0; overflow: hidden;">
                  <svg style="width: 100%; height: auto; display: block; transform: scale(2); transform-origin: top center"
                     viewBox="0 0 2880 48" fill="#d08750" xmlns="http://www.w3.org/2000/svg">
                     <path d="M0 48h2880V0h-720C1442.5 52 720 0 720 0H0v48z" fill="#d08750"></path>
                  </svg>
               </div>
            </div>
            <div id="roadmap" class="w-100 py-5 roadmap position-relative" style="">
               <div class="container">
                  <div class="row mb-3">
                     <div class="col-12 text-center ">
                        <h2 class="violet">Road Map</h2>
                     </div>
                  </div>
                  <ul class="row">
                     <li class="col-12 col-sm-6 col-md-3 d-flex align-items-center mb-2">
                        <font-awesome-icon icon="bolt" class="text-success mr-2"/>
                        <h6 class="mb-0">Babythundercake is born.</h6>
                     </li>
                     <li class="col-12 col-sm-6 col-md-3 d-flex align-items-center mb-2">
                        <font-awesome-icon icon="bolt" class="text-success mr-2"/>
                        <h6 class="mb-0"> Website launched</h6>
                     </li>
                     <li class="col-12 col-sm-6 col-md-3 d-flex align-items-center mb-2">
                        <font-awesome-icon icon="bolt" class="text-success mr-2"/>
                        <h6 class="mb-0">Brand development</h6>
                     </li>
                     <li class="col-12 col-sm-6 col-md-3 d-flex align-items-center mb-2">
                        <font-awesome-icon icon="times-circle" class="text-secondary mr-2"/>
                        <h6 class="mb-0">NFT Game Development</h6>
                     </li>
                     <li class="col-12 col-sm-6 col-md-3 d-flex align-items-center mb-2">
                        <font-awesome-icon icon="times-circle" class="text-secondary mr-2"/>
                        <h6 class="mb-0">NFT GAME</h6>
                     </li>
                     <li class="col-12 col-sm-6 col-md-3 d-flex align-items-center mb-2">
                        <font-awesome-icon icon="bolt" class="text-success mr-2"/>
                        <h6 class="mb-0"> Socials created</h6>
                     </li>
                     <li class="col-12 col-sm-6 col-md-3 d-flex align-items-center mb-2">
                        <font-awesome-icon icon="bolt" class="text-success mr-2"/>
                        <h6 class="mb-0">Organic awareness campaign</h6>
                     </li>
                     <li class="col-12 col-sm-6 col-md-3 d-flex align-items-center mb-2">
                        <font-awesome-icon icon="bolt" class="text-success mr-2"/>
                        <h6 class="mb-0">Babythundercake Dashboard (earnings tracking)</h6>
                     </li>
                     <li class="col-12 col-sm-6 col-md-3 d-flex align-items-center mb-2">
                        <font-awesome-icon icon="bolt" class="text-success mr-2"/>
                        <h6 class="mb-0">Influencers</h6>
                     </li>
                     <li class="col-12 col-sm-6 col-md-3 d-flex align-items-center mb-2">
                        <font-awesome-icon icon="bolt" class="text-success mr-2"/>
                        <h6 class="mb-0">PooCoin Ads</h6>
                     </li>
                     <li class="col-12 col-sm-6 col-md-3 d-flex align-items-center mb-2">
                        <font-awesome-icon icon="times-circle" class="text-secondary mr-2"/>
                        <h6 class="mb-0">DexTools Trending</h6>
                     </li>
                     <li class="col-12 col-sm-6 col-md-3 d-flex align-items-center mb-2">
                        <font-awesome-icon icon="times-circle" class="text-secondary mr-2"/>
                        <h6 class="mb-0">CoinGecko</h6>
                     </li>
                     <li class="col-12 col-sm-6 col-md-3 d-flex align-items-center mb-2">
                        <font-awesome-icon icon="times-circle" class="text-secondary mr-2"/>
                        <h6 class="mb-0">CoinMarketCap</h6>
                     </li>
                     <li class="col-12 col-sm-6 col-md-3 d-flex align-items-center mb-2">
                        <font-awesome-icon icon="times-circle" class="text-secondary mr-2"/>
                        <h6 class="mb-0">Website Revamp</h6>
                     </li>
                     <li class="col-12 col-sm-6 col-md-3 d-flex align-items-center mb-2">
                        <font-awesome-icon icon="bolt" class="text-success mr-2"/>
                        <h6 class="mb-0">Community Building</h6>
                     </li>
                     <li class="col-12 col-sm-6 col-md-3 d-flex align-items-center mb-2">
                        <font-awesome-icon icon="times-circle" class="text-secondary mr-2"/>
                        <h6 class="mb-0">Massive Babythundercake pay-outs</h6>
                     </li>
                     <li class="col-12 col-sm-6 col-md-3 d-flex align-items-center mb-2">
                        <font-awesome-icon icon="times-circle" class="text-secondary mr-2"/>
                        <h6 class="mb-0">Certik Audit</h6>
                     </li>
                     <li class="col-12 col-sm-6 col-md-3 d-flex align-items-center mb-2">
                        <font-awesome-icon icon="times-circle" class="text-secondary mr-2"/>
                        <h6 class="mb-0"> Influencer marketing push</h6>
                     </li>
                     <li class="col-12 col-sm-6 col-md-3 d-flex align-items-center mb-2">
                        <font-awesome-icon icon="bolt" class="text-success mr-2"/>
                        <h6 class="mb-0">Baby Babythundercake Swap</h6>
                     </li>
                     <li class="col-12 col-sm-6 col-md-3 d-flex align-items-center mb-2">
                        <font-awesome-icon icon="times-circle" class="text-secondary mr-2"/>
                        <h6 class="mb-0">Massive influencer partnerships</h6>
                     </li>
                     <li class="col-12 col-sm-6 col-md-3 d-flex align-items-center mb-2">
                        <font-awesome-icon icon="times-circle" class="text-secondary mr-2"/>
                        <h6 class="mb-0">Listings on major CEX</h6>
                     </li>
                  </ul>
               </div>
            </div>
         </div>
         <footer class="khaki pt-3">
            <div class="container">
               <div class="py-3">
                  <div class="row ">
                     <div class="col-12 col-md-8">
                        <!-- Logo -->
                        <div class="mb-4 d-flex justify-content-between w-100">
                           <div class="d-flex align-items-center ">
                              <img width="70" class="d-block mr-3" src="@/assets/images/babythundercake.png" alt="Babythundercake">
                              <div class="">
                                 <h3 class="violet" style="font-size: 104%; margin: 0">Babythundercake</h3>
                                 <p class="text-white small mb-0">Hold Babythundercake and earn $CAKE and $THUNDERCAKE automatically or claim your
                                    rewards
                                    on our website!
                                 </p>
                              </div>
                           </div>
                        </div>
                     </div>
                     <div class="col-12 col-md-4">
                        <div class="d-flex flex-column">
                           <a class="text-white  m-1 mr-5 d-flex align-items-center" target="_blank"
                              href="https://t.me/BabyThunderCake">
                              <font-awesome-icon :icon="['fab', 'telegram-plane']" class="mr-2 mb-2"/>
                              <h5 style="font-size: 100%">BabyThunderCake</h5>
                           </a>
                           <a class="text-white  m-1 d-flex align-items-center" target="_blank"
                              href="https://twitter.com/BabyThunderCake">
                              <font-awesome-icon :icon="['fab', 'twitter']" class="mr-2 mb-2"/>
                              <h5 style="font-size: 100%">Twitter BBTC</h5>
                           </a>
                        </div>
                     </div>
                  </div>
               </div>
               <!-- Copyright -->
            </div>
         </footer>
      </div>
  </div>
</template>
<script>
import Navbar from '@/shared/Navbar.vue'
export default {
  components: {Navbar},
  data: () => ({
    name: 'HelloWorld',
    props: {
      msg: String,
      toggled: false,
    }
  }),
  methods: {
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
