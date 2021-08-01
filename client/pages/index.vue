<template>
  <div>
    <div class="content-1 font-white">
      <div class="hidden-mobile text-center">
        <a-row type="flex">
          <a-col :span="24" class="text-center">
            <span><img src="https://usenobi.com/img/logo.svg" alt="NOBI - Grow Crypto The Easy Way" style="width: 100px;" /></span>
          </a-col>
        </a-row>
        <a-row style="margin: 2em 0;">
          <span>
            <img src="https://usenobi.com/img/Ilust-1-update.svg" style="height: 250px;" />
          </span>
        </a-row>
        <a-row style="margin: 2em 0;">
          <span style="font-weight: bold; font-size: 1rem; margin-bottom: 0.5em;">Grow Crypto The Easy
          Way</span>
        </a-row>
        <a-row style="margin: 2em 0;">
          <span style="font-size: 1rem; margin-bottom: 0.5em;">Automate your crypto trading strategy and take your emotion out of the equation
          </span>
        </a-row>
        <a-row>
          <a-col>
            <span style="margin-right: 1em;">
              <img style="width: 140px; " src="https://usenobi.com/img/appstore-badge-update.svg" alt="">
            </span>
            <span>
              <img style="width: 140px;" src="https://usenobi.com/img/playstore-badge-update.svg" alt="">
            </span>
          </a-col>
        </a-row>
      </div>

      <div class="hidden">
        <a-row>
          <a-col :span="12">
            <span><img src="https://usenobi.com/img/logo.svg" alt="NOBI - Grow Crypto The Easy Way" style="width: 100px;" /></span>
          </a-col>
          <a-col :span="12" style="text-align:right;">
            <span class="">Strategy Maker</span> <span style="color: gray; font-size: larger;"> | </span>
            <span class="">Blog</span>
          </a-col>
        </a-row>

        <a-row style="margin-top: 5em">
          <a-col :span="20">
            <span style="display: block; font-weight: bold; font-size: 2.5rem; margin-bottom: 0.5em;">Grow Crypto The Easy
              Way</span>
            <span style="display: block; font-size: 1.5rem; margin-bottom: 2em;">Automate your crypto trading strategy and
              take your emotion
              out of the
              equation</span>
            
            <span style="margin-right: 1em;">
              <img style="width: 140px; " src="https://usenobi.com/img/appstore-badge-update.svg" alt="">
            </span>
            <span>
              <img style="width: 140px;" src="https://usenobi.com/img/playstore-badge-update.svg" alt="">
            </span>
          </a-col>
          <a-col :span="4" style="text-align:right;">
            <span>
              <img src="https://usenobi.com/img/Ilust-1-update.svg" style="height: 250px;" />
            </span>
          </a-col>
        </a-row>
      </div>
      
    </div>
    <div class="content-2">
      <div class="text-center font-white" style="margin-bottom:3rem;">
        <a-radio-group>
          <a-radio-button>
            Strategy
          </a-radio-button>
          <a-radio-button>
            Staking
          </a-radio-button>
          <a-radio-button>
            Saving
          </a-radio-button>
        </a-radio-group>
      </div>
      <div class="hidden">
        <table id="strategy-table" class="font-white">
          <tr>
            <th>Strategy</th>
            <th>Marketcap</th>
            <th>Volume</th>
            <th>Est. Annual Yield</th>
            <th>Node Collateral</th>
            <th>Hosted Node</th>
            <th>1 Month</th>
            <th></th>
            <th></th>
          </tr>
          <tr>
            <td>DASH</td>
            <td>Nova Kapital</td>
            <td>$148,574.33</td>
            <td style="color :#ec3d66">-12.45%</td>
            <td style="color :#ec3d66">-2.12%</td>
            <td>+212.3%</td>
            <td>+212.3%</td>
            <td>+212.3%</td>
            <td>+212.3%</td>
          </tr>
          <tr>
            <td>SMART</td>
            <td>Nova Kapital</td>
            <td>$148,574.33</td>
            <td style="color :#ec3d66">-2.36%</td>
            <td style="color :#ec3d66">-1.45%</td>
            <td>+212.3%</td>
            <td>+212.3%</td>
            <td>+212.3%</td>
            <td>+212.3%</td>
          </tr>
          <tr>
            <td>ZCOIN</td>
            <td>Nova Kapital</td>
            <td>$148,574.33</td>
            <td style="color :#ec3d66">-1,66%</td>
            <td style="color :#ec3d66">-1.21%</td>
            <td>+212.3%</td>
            <td>+212.3%</td>
            <td>+212.3%</td>
            <td>+212.3%</td>
          </tr>
          <tr>
            <td>Nova Obscura</td>
            <td>Nova Kapital</td>
            <td>$148,574.33</td>
            <td style="color :#ec3d66">-7.50%</td>
            <td style="color :#ec3d66">-2.22%</td>
            <td>+212.3%</td>
            <td>+212.3%</td>
            <td>+212.3%</td>
            <td>+212.3%</td>
          </tr>
          <tr>
            <td>Neu Oscilator</td>
            <td>Nova Kapital</td>
            <td>$148,574.33</td>
            <td style="color :#ec3d66">-8.92%</td>
            <td style="color :#ec3d66">-3.23%</td>
            <td>+212.3%</td>
            <td>+212.3%</td>
            <td>+212.3%</td>
            <td>+212.3%</td>
          </tr>
        </table>
      </div>
      <div class="hidden-mobile">
        <table id="strategy-table" class="font-white">
          <tr>
            <th>Strategy</th>
            <th>Asset Following Strategy</th>
          </tr>
          <tr>
            <td>DASH</td>
            <td>$148,574.33</td>
          </tr>
          <tr>
            <td>SMART</td>
            <td>$148,574.33</td>
          </tr>
          <tr>
            <td>ZCOIN</td>
            <td>$148,574.33</td>
          </tr>
          <tr>
            <td>Nova Obscura</td>
            <td>$148,574.33</td>
          </tr>
          <tr>
            <td>Neu Oscilator</td>
            <td>$148,574.33</td>
          </tr>
        </table>
      </div>
      <a-row style="margin-top: 3em;">
        <a-col :md="10">
        </a-col>
        <a-col :md="14">
          <span class="button-mobile">
            <a-button class="button-explore">
              <span>Explore More </span> 
              <span style="margin-left:3em"> | </span>
              <span style="margin-left:0.5em"> <a-icon type="arrow-right" /> </span>
            </a-button>
          </span>
        </a-col>
      </a-row>
    </div>

    <div class="content-3">
      <a-row>
        <a-col :md="10">
          <img src="https://usenobi.com/img/ilust-3-update.svg" alt="" style="width: 200px; margin-left: 5em">
        </a-col>
        <a-col :md="14">
          <span style="display: block; font-weight: bold; font-size: 2.5rem;">Create Your Own Strategy</span>
          <span style="display: block; font-weight: bold; font-size: 2.5rem;">And Become a
            Strategy Marker</span>
          <span style="display: block; margin-top:2em;" class="button-mobile">
            <a-button class="button-explore">
              <span>Learn More </span> 
              <span style="margin-left:3em"> | </span>
              <span style="margin-left:0.5em"> <a-icon type="arrow-right" /> </span>
            </a-button>
          </span>
        </a-col>
      </a-row>
    </div>

    <div class="content-4 font-white">
      <a-row>
        <span style="font-weight: bold; font-size: 2.5rem;">Growing Crypto Has Never Been This Easy!</span>
      </a-row>
      <a-row style="margin-top:1em;">
        <span style="font-size: 1rem;">NOBI makes it safe and easy to trade with our Robo Trading! Just choose the available strategy and let our strategy makers do the magic for you.</span>
      </a-row>
      <a-row type="flex">
        <a-col :md="7" class="text-center .image-mobile">
          <span class="image-display">
            <img src="https://usenobi.com/img/number1-grow.svg" alt="" style="width: 200px;">
          </span>
          <span style="font-weight: bold; font-size: 1rem;">
            Download App
          </span>
        </a-col>
        <a-col :md="1" style="display:flex; align-items:center;" class="hidden">
          <span> <a-icon style="font-size: 2rem" type="arrow-right" /> </span>
        </a-col>
        <a-col :md="8" class="text-center .image-mobile">
          <span class="image-display">
            <img src="https://usenobi.com/img/number2-grow.svg" alt="" style="width: 200px;">
          </span>
          <span style="font-weight: bold; font-size: 1rem;">
            Fund Your Wallet
          </span>
        </a-col>
        <a-col :md="1" style="display:flex; align-items:center;" class="hidden">
          <span> <a-icon style="font-size: 2rem" type="arrow-right" /> </span>
        </a-col>
        <a-col :md="7" class="text-center .image-mobile">
           <span class="image-display">
            <img src="https://usenobi.com/img/number3-grow.svg" alt="" style="width: 200px;">
          </span>
          <span style="font-weight: bold; font-size: 1rem;">
            Start Growing Crypto
          </span>
        </a-col>
      </a-row>
    </div>

    <div class="content-5 font-white">
      <a-row type="flex">
        <a-col :md="10" class="text-center image-mobile">
          <span>
            <img src="https://usenobi.com/img/ilust-4-update.svg" alt="" style="width: 200px;">
          </span>
        </a-col>
        <a-col :md="14">
          <span style="font-weight: bold; font-size: 2rem; display:block;">
            Start With as Little as B0.01
          </span>
          <span style="font-size: 1rem; display:block; margin-top:2em">
            You can start growing your bitcoin and other cryptocurrencies from as low as B 0.01. Trade better by following our Trading Strategy. Our Technology will help you minimize risks and enhance your gain. Simply choose & follow!
          </span>
        </a-col>
      </a-row>
    </div>

    <div class="content-6">
      <a-row class="text-center">
        <span style="font-weight: bold; font-size: 2rem;">Powered By Industry Best</span>
      </a-row>
      <a-row type="flex" class="text-center">
        <a-col :md="8" style="margin-top:1em" class="image-mobile">
          <span>
            <img src="https://usenobi.com/img/binance-logo-v2-alt.png" alt="" style="width: 200px;">
          </span>
        </a-col>
        <a-col :md="8" style="margin-top:1em" class="image-mobile">
          <span>
            <img src="https://usenobi.com/img/binance-logo-v2-alt.png" alt="" style="width: 200px;">
          </span>
        </a-col>
        <a-col :md="8" style="margin-top:1em" class="image-mobile">
          <span>
            <img src="https://usenobi.com/img/binance-logo-v2-alt.png" alt="" style="width: 200px;">
          </span>
        </a-col>
      </a-row>
    </div>

    <div class="content-7 font-white">
      <a-row class="text-center">
        <span style="font-weight: bold; font-size: 2rem;">So, What Are You Waiting For?</span>
      </a-row>
      <a-row class="text-center" style="margin-top:3em">
        <span style="font-weight: bold; font-size: 1rem;">Start growing your crypto and join countless crypto believers who have successfully grow with us!</span>
      </a-row>
      <a-row class="text-center" style="margin-top:3em">
        <span style="margin-right: 1em;">
          <img style="width: 140px; " src="https://usenobi.com/img/appstore-badge-update.svg" alt="">
        </span>
        <span>
          <img style="width: 140px;" src="https://usenobi.com/img/playstore-badge-update.svg" alt="">
        </span>
      </a-row>
      <a-row class="text-center" style="margin-top:3em">
        <span style="font-size: 0.5rem; display:block">Risk warning: Buying, selling, holding and partaking in trading of cryptocurrencies are activities that are subject to high market risk</span>
        <span style="font-size: 0.5rem; display:block">The volatile and unpredictable nature of the price of cryptocurrencies may result in significant loss.</span>
      </a-row>
    </div>

    <div class="content-8 font-white">
      <div class="hidden-mobile">
        <a-row>
          <span><img src="https://usenobi.com/img/logo.svg" alt="NOBI - Grow Crypto The Easy Way" style="width: 100px;" /></span>
        </a-row>
        <a-row style="margin-top:2em">
          <span>Copyright 2020 Nobi. All trademarks and copyrights belong to their respective owners</span>
        </a-row>
        <a-row style="margin-top:3em">
          <span>Join Our Community</span>
        </a-row>
      </div>
    </div>
  </div>
</template>

<script>
</script>

<style scoped>
    .font-white {
      color: white;
    }

    .pointer {
      cursor: pointer;
    }

    .text-center {
      text-align: center;
    }

    .image-display {
      display: block;
    }

    .content-1 {
      background-image: linear-gradient(#010103, #09152d);
      padding: 3em 10em 10em;
    }

    .content-2 {
      padding: 5em 2em;
      background-color: black;    
    }

    .content-3 {
      padding: 3em 2em;
      background-color: white;    
    }

    .content-4 {
      padding: 3em 10em;
      background-color: black;    
    }

    .content-5 {
      padding: 3em 10em;
      background-color: #055df3;    
    }

    .content-6 {
      padding: 3em 4em;
      background-color: white;    
    }

    .content-7 {
      padding: 3em 4em;
      background-color: #09152d;    
    }

    #strategy-table {
      border-collapse: collapse;
      width: 100%;
    }

    #strategy-table td,
    #strategy-table th {
      border: 1px solid #1a1a1a;
      padding: 8px;
    }

    #strategy-table tr:nth-child(odd) {
      background-color: #1a1a1a;
    }

    #strategy-table td:nth-child(1n+6) {
      color: #04bf91;
    }

    #strategy-table td:nth-child(1) {
      text-decoration: underline;
    }

    #strategy-table th {
      padding-top: 12px;
      padding-bottom: 12px;
      text-align: left;
      background-color: #1a1a1a;
    }

    .button-explore {
      border: none;
      color: white;
      text-align: center;
      text-decoration: none;
      font-size: 16px;
      border-radius: 10px;
      height: 40px;
      background-color: #055df3;
    }

    .hidden-mobile {
      display: none !important;
    }

    .ant-radio-button-wrapper-checked:not(.ant-radio-button-wrapper-disabled) {
      color: white;
      background-color: black;
    }

    .ant-radio-button-wrapper-checked:not(.ant-radio-button-wrapper-disabled):first-child {
      background-color: #055df3;
    }

    .content-8 {
      text-align: center;
      padding: 3em 2em;
      background-color: black;    
    }
  
  @media only screen and (max-width: 768px) {
    .hidden {
      display: none !important;
    }
    .hidden-mobile {
      display: unset !important;
    }
    .button-mobile {
      text-align: center;
    }
    .image-mobile {
      width: 100%;
    }
    .image-display {
      display: unset;
    }

    .content-1 {
      background-image: linear-gradient(#010103, #09152d);
      padding: 3em 2em 10em;
    }

    .content-2 {
      text-align: center;
      padding: 5em 2em;
      background-color: black;    
    }

    .content-3 {
      text-align: center;
      padding: 3em 2em;
      background-color: white;    
    }

    .content-4 {
      text-align: center;
      padding: 3em 2em;
      background-color: black;    
    }

    .content-5 {
      text-align: center;
      padding: 3em 2em;
      background-color: #055df3;    
    }

    .content-6 {
      text-align: center;
      padding: 3em 2em;
      background-color: white;    
    }

    .content-7 {
      text-align: center;
      padding: 3em 2em;
      background-color: #09152d;    
    }

    .content-8 {
      text-align: center;
      padding: 3em 2em;
      background-color: black;    
    }

    #strategy-table th {
      padding-top: 12px;
      padding-bottom: 12px;
      text-align: center;
      background-color: #1a1a1a;
    }
  }
</style>
