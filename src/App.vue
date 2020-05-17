<template>
  <div id="app">
    <el-row>
      <el-col :span="24">
        <div class="head-wrap">Just My Socks</div>
      </el-col>
    </el-row>
    <nav id="nav" class="navbar-main" role="navigation"></nav>
    <div class="row row-product-selection">
      <div class="col-xs-12">
        <div id="order-premium_comparison">
          <div class="main-container price-01">
            <div class="txt-center">
              <h3>
                Just My Socks
              </h3>
            </div>
            <div class="txt-center">
              <h5>
                最新Just My Socks优惠码：JMS9272283, 立即优惠5.2%
              </h5>
            </div>
            <div id="products" class="price-table-container">
              <ul>
                <li id="product1">
                  <div class="price-table">
                    <div class="top-head">
                      <div class="top-area">
                        <h4 id="product1-name">500G/洛杉矶</h4>
                      </div>
                      <div class="price-area">
                        <div class="price" id="product1-price">
                          <span>$5.88</span>/月
                          <br>
                        </div>
                        <a href="https://justmysocks2.net/members/aff.php?aff=5512&pid=2?language=chinese" class="order-button" id="product1-order-button">
                          点击购买
                        </a>
                      </div>
                    </div>
                    <ul>
                      <li id="product1-description">
                        500GB/月，2.5Gbps带宽｜限5台设备
                      </li>
                    </ul>
                  </div>
                </li>
                <li id="product2">
                  <div class="price-table">
                    <div class="top-head">
                      <div class="top-area">
                        <h4 id="product2-name">1000G/洛杉矶</h4>
                      </div>
                      <div class="price-area">
                        <div class="price" id="product2-price">
                          <span>$9.88</span>/月
                          <br>
                        </div>
                        <a href="https://justmysocks2.net/members/aff.php?aff=5512&pid=3?language=chinese" class="order-button" id="product2-order-button">
                          点击购买
                        </a>
                      </div>
                    </div>
                    <ul>
                      <li id="product2-description">
                        1TB/月，5Gbps带宽｜设备数量无限制
                      </li>
                    </ul>
                  </div>
                </li>
                <li id="product3">
                  <div class="price-table">
                    <div class="top-head">
                      <div class="top-area">
                        <h4 id="product3-name">5000G/洛杉矶</h4>
                      </div>
                      <div class="price-area">
                        <div class="price" id="product3-price">
                          <span>$48.99</span>/月
                          <br>
                        </div>
                        <a href="https://justmysocks2.net/members/aff.php?aff=5512&pid=4?language=chinese" class="order-button" id="product3-order-button">
                          点击购买
                        </a>
                      </div>
                    </div>
                    <ul>
                      <li id="product3-description">
                        5TB/月，5Gbps带宽｜设备数量无限制
                      </li>
                    </ul>
                  </div>
                </li>
              </ul>
              <ul>
                <li id="product4">
                  <div class="price-table">
                    <div class="top-head">
                      <div class="top-area">
                        <h4 id="product4-name">100G/东京</h4>
                      </div>
                      <div class="price-area">
                        <div class="price" id="product4-price">
                          <span>$29.99</span>/月
                          <br>
                        </div>
                        <a href="https://justmysocks2.net/members/aff.php?aff=5512&pid=5?language=chinese" class="order-button" id="product4-order-button">
                          点击购买
                        </a>
                      </div>
                    </div>
                    <ul>
                      <li id="product4-description">
                        100G/月，100Mbps带宽｜限3台设备
                      </li>
                    </ul>
                  </div>
                </li>
                <li id="product5">
                  <div class="price-table">
                    <div class="top-head">
                      <div class="top-area">
                        <h4 id="product5-name">500G/东京</h4>
                      </div>
                      <div class="price-area">
                        <div class="price" id="product5-price">
                          <span>$135.99</span>/月
                          <br>
                        </div>
                        <a href="https://justmysocks2.net/members/aff.php?aff=5512&pid=6?language=chinese" class="order-button" id="product5-order-button">
                          点击购买
                        </a>
                      </div>
                    </div>
                    <ul>
                      <li id="product5-description">
                        500G/月，200Mbps带宽｜限5台设备
                      </li>
                    </ul>
                  </div>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
    <section id="footer">
      <div class="container">
        <p>Copyright © 2019 Just My Socks. All Rights Reserved.</p>
        <p><a href="https://justmysocks2.cn">justmysocks2.cn</a>并非 Just My Socks 官网，仅翻译整理。Just My Socks 官网地址：<a href="https://justmysocks2.net/members/aff.php?aff=5512&gid=1?language=chinese">Just My Socks</a></p>
      </div>
    </section>
  </div>
</template>

<script>
  export default {
    name: 'app',
  }

</script>

<style>
  /**
 * Premium Slider order form style sheet
 *
 * Contains styling specific to the Premium Slider order template.
 *
 * @project   WHMCS
 * @version   1.0
 * @author    WHMCS Limited <development@whmcs.com>
 * @copyright Copyright (c) WHMCS Limited 2005-2015
 * @license   http://www.whmcs.com/license/
 * @link      http://www.whmcs.com/
 */

  div#order-premium_comparison {
    padding:0 0 0 0;
    margin:0 0 30px 0;
    height: 100%;
    width: 100%;
    line-height:18px;
    font-size:14px;
    color:#666666;
    text-rendering: optimizeLegibility !important;
  }

  /* Text Styling */

  #order-premium_comparison a,
  #order-premium_comparison a:hover,
  #order-premium_comparison a:active,
  #order-premium_comparison a:visited,
  #order-premium_comparison a:link {
    outline:none;
    transition: all 0.5s ease 0s;
    -webkit-transition: all 0.5s ease 0s;
    -moz-transition: all 0.5s ease 0s;
  }
  #order-premium_comparison div,
  #order-premium_comparison ul,
  #order-premium_comparison li {
    padding:0 0 0 0;
    margin:0 0 0 0;
  }

  /* Headings */

  #order-premium_comparison h1 {
  }
  #order-premium_comparison h2 {
  }
  #order-premium_comparison h3 {
    padding:0 0 0 0;
    margin:0;
    font-size:32px;
    line-height:38px;
    font-weight:bold;
    color:#333333;
  }
  #order-premium_comparison h4 {
    padding:0 0 0 0;
    margin:10px 0;
    font-size:24px;
    color:#333333;
  }
  #order-premium_comparison h5 {
    padding:0 0 0 0;
    margin:5px 0;
    font-size:16px;
    color:#666666;
  }

  #order-premium_comparison .txt-center {
    text-align:center;
  }

  #order-premium_comparison .alert {
    margin-top: 70px;
    padding: 15px;
  }

  #order-premium_comparison .main-container {
    padding:0 2% 40px 2%;
    margin:0 auto;
  }
  #order-premium_comparison .main-container.price-01 {
    font-size:14px;
    line-height:17px;
  }
  #order-premium_comparison .main-container.price-01 h3,
  #order-premium_comparison .main-container.price-01 h5 {
    font-weight:normal;
  }

  #order-premium_comparison .price-table-container {
    padding:10px 0 0 0;
    margin:0 0 0 0;
  }
  #order-premium_comparison .price-table-container ul {
    padding:0 0 0 0;
    margin:0 0 0 0;
    list-style:none;
    text-align:center;
  }
  #order-premium_comparison .price-table-container ul li {
    padding:30px 10px 5px 10px;
    margin:0 0 0 0;
    display:inline-block;
    background:url(assets/shadow-btm.png) no-repeat center bottom;
  }
  #order-premium_comparison .price-table-container .price-table {
    padding:0 0 0 0;
    margin:0 0 0 0;
    width: 270px;
    min-width: 270px;
    background:#ffffff;
    -moz-border-radius:5px;
    -webkit-border-radius:5px;
    border-radius:5px;
    -webkit-box-shadow: 0 0 2px 0 rgba(0,0,0,0.30);
    -moz-box-shadow: 0 0 2px 0 rgba(0,0,0,0.30);
    box-shadow: 0 0 2px 0 rgba(0,0,0,0.30);
  }
  #order-premium_comparison .price-table-container .price-table.active {
    margin:-30px 0 0 0;
    width:245px;
  }
  #order-premium_comparison .price-table-container .price-table .top-head {
    /* Old browsers */
    background: #006699;
    /* FF3.6+ */
    background: -moz-linear-gradient(top,  #006699 0%, #004c66 100%);
    /* Chrome,Safari4+ */
    background: -webkit-gradient(linear, left top, left bottom, color-stop(0%,#006699), color-stop(100%,#004c66));
    /* Chrome10+,Safari5.1+ */
    background: -webkit-linear-gradient(top,  #006699 0%,#004c66 100%);
    /* Opera 11.10+ */
    background: -o-linear-gradient(top,  #006699 0%,#004c66 100%);
    /* IE10+ */
    background: -ms-linear-gradient(top,  #006699 0%,#004c66 100%);
    /* W3C */
    background: linear-gradient(to bottom,  #006699 0%,#004c66 100%);
    /* IE6-9 */
    filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#006699', endColorstr='#004c66',GradientType=0);
    border-radius:5px 5px 0 0;
    -moz-border-radius:5px 5px 0 0;
    -webkit-border-radius:5px 5px 0 0;
  }
  #order-premium_comparison .price-table-container .price-table .top-head .top-area {
    padding:15px 0;
    margin:0 0 0 0;
    border-bottom:1px solid #004662;
    text-shadow: 0 1px 2px rgba(0,0,0,0.4);
  }
  #order-premium_comparison .price-table-container .price-table .top-head .top-area h4 {
    padding:0 0 0 0;
    margin:0 0 0 0;
    font-weight:normal;
    color:#ffffff;
    line-height:29px;
  }
  #order-premium_comparison .price-table-container .price-table .top-head .top-area p {
    padding:5px 0 0 0;
    margin:0 0 0 0;
    color:#80a7ba;
    font-size:13px;
    line-height:20px;
  }
  #order-premium_comparison .price-table-container .price-table .top-head .price-area {
    padding:15px 0;
    margin:0 0 0 0;
    border-top:1px solid #12688d;
    text-shadow: 0 1px 2px rgba(0,0,0,0.4);
    color:#ffffbf;
    font-size:16px;
  }
  #order-premium_comparison .price-table-container .price-table .top-head .price-area .price {
    padding:10px 0 10px 0;
  }
  #order-premium_comparison .price-table-container .price-table .top-head .price-area .price span {
    font-size:38px;
  }
  #order-premium_comparison .price-table-container .order-button,
  #order-premium_comparison .price-table-container .order-button:hover {
    padding:13px 0;
    margin:10px 25px;
    font-size:16px;
    color:#ffffff;
    display:block;
    font-weight:normal;
    /* Old browsers */
    background: #4a92b7;
    /* FF3.6+ */
    background: -moz-linear-gradient(top,  #4a92b7 0%, #006699 100%);
    /* Chrome,Safari4+ */
    background: -webkit-gradient(linear, left top, left bottom, color-stop(0%,#4a92b7), color-stop(100%,#006699));
    /* Chrome10+,Safari5.1+ */
    background: -webkit-linear-gradient(top,  #4a92b7 0%,#006699 100%);
    /* Opera 11.10+ */
    background: -o-linear-gradient(top,  #4a92b7 0%,#006699 100%);
    /* IE10+ */
    background: -ms-linear-gradient(top,  #4a92b7 0%,#006699 100%);
    /* W3C */
    background: linear-gradient(to bottom,  #4a92b7 0%,#006699 100%);
    /* IE6-9 */
    filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#4a92b7', endColorstr='#006699',GradientType=0);
    -webkit-border-radius:3px;
    -moz-border-radius:3px;
    border-radius:3px;
    text-decoration:none;
    text-shadow: 0 0 1px rgba(0,0,0,0.4);
    -webkit-box-shadow: 0 1px 2px 0 rgba(0,0,0,0.40);
    -moz-box-shadow: 0 1px 2px 0 rgba(0,0,0,0.40);
    box-shadow: 0 1px 2px 0 rgba(0,0,0,0.40);
  }
  #order-premium_comparison .price-table-container .order-button.unavailable:hover {
    cursor: not-allowed;
    /* Old browsers */
    background: #404A53;
    /* FF3.6+ */
    background: -moz-linear-gradient(top,  #404A53 0%, #949499 100%);
    /* Chrome,Safari4+ */
    background: -webkit-gradient(linear, left top, left bottom, color-stop(0%,#404A53), color-stop(100%,#949499));
    /* Chrome10+,Safari5.1+ */
    background: -webkit-linear-gradient(top,  #404A53 0%,#949499 100%);
    /* Opera 11.10+ */
    background: -o-linear-gradient(top,  #404A53 0%,#949499 100%);
    /* IE10+ */
    background: -ms-linear-gradient(top,  #404A53 0%,#949499 100%);
    /* W3C */
    background: linear-gradient(to bottom,  #404A53 0%,#949499 100%);
    /* IE6-9 */
    filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#404A53', endColorstr='#949499',GradientType=0);
  }
  #order-premium_comparison .price-table-container .price-table ul {
    padding: 4px 10px 10px 10px;
    margin:0 0 0 0;
    list-style:none;
  }
  #order-premium_comparison .price-table-container .price-table ul li {
    padding:17px 0 15px 0;
    margin:0 0 0 0;
    width:100%;
    border-bottom:1px solid #d9d9d9;
    color:#333333;
    text-align:center;
    line-height:16px;
    font-size:14px;
    background:none;
  }
  #order-premium_comparison .price-table-container .price-table ul li a {
    color:#006699;
  }
  #order-premium_comparison .price-table-container .price-table ul li:last-child {
    border-bottom:0;
  }
  #order-premium_comparison .price-table-container .price-table .popular-plan {
    padding:7px 0 5px 0;
    background:rgba(0,0,0,0.2);
    border-bottom:1px solid #004662;
    color:#a3d900;
    font-size:13px;
    text-transform:uppercase;
  }

  #order-premium_comparison .includes-features {
    margin:0 auto;
    width:100%;
    max-width:780px;
    padding-top:10px;
  }
  #order-premium_comparison .includes-features .head-area {
    padding:0 0 0 0;
    margin:0 0 0 0;
    text-align:center;
    /*background:url(../img/head-bg.png) no-repeat center center;*/
    background-size:100% auto;
  }
  #order-premium_comparison .includes-features .head-area span {
    padding:0 20px;
    margin:0 0 0 0;
    display:inline-table;
    background:#ffffff;
  }
  #order-premium_comparison .main-container.price-01 .includes-features .head-area span {
    background:#f3f3f3;
  }
  #order-premium_comparison .includes-features ul.list-features {
    padding:20px 0 0 0;
    margin:0 0 0 0;
    list-style:none;
  }
  #order-premium_comparison .includes-features ul.list-features li {
    padding:0 0 0 22px;
    margin:5px 0;
    width:33%;
    display:inline-table;
    /*background:url(../img/tick.png) no-repeat;*/
  }

  /* This media query is written for iPad and tablets */
  @media (max-width: 991px) {
    #order-premium_comparison .includes-features ul.list-features li {
      width:48%;
    }
  }

  /* This media query is written for Mobile only */
  @media (max-width: 600px) {
    #order-premium_comparison .price-table-container .price-table {
      margin:0 0 0 0;
      width: 300px;
    }
    #order-premium_comparison .price-table-container .price-table.active {
      margin:0 0 0 0;
      width:300px;
    }
  }

  /* This media query is written for Mobile only */
  @media (max-width: 480px) {
    #order-premium_comparison .includes-features ul.list-features li {
      width:100%;
    }
  }

  /* Sidebar */

  html, body {
    overflow-x: hidden; /* Prevent scroll on narrow devices */
  }

  .row-product-selection {
    position: relative;
    left: 0;
    -webkit-transition: all .25s ease-out;
    -o-transition: all .25s ease-out;
    transition: all .25s ease-out;
  }

  .product-selection-sidebar {
    position: absolute;
    top: 0;
    left: -300px;
    width: 300px;
    display: none;
  }

  #btnShowSidebar {
    margin: 0 0 20px 0;
  }

  .navbar-main {
    margin-bottom: 0;
    background-color: #0e5077;
    border: 0;
    min-height: 38px;
    font-family: Raleway,"Helvetica Neue",Helvetica,Arial,sans-serif;
    font-size: 15px;
  }
  section#footer {
    margin: 0;
    padding: 0 0;
    background-color: #f8f8f8;
    border-top: 1px solid #ddd;
    color: #666;
    font-size: .9em;
  }

  .container {
    padding-right: 15px;
    padding-left: 100px;
    margin-right: auto;
    margin-left: auto;
  }
  .head-wrap{
    margin-left: 100px;
    font-family: sans-serif;
    font-weight: 400;
    font-size: 2.6em;
    white-space: nowrap;
    color: #0e5077;
  }

</style>