---
title: "テレワーク実践ガイド"
description: "初めてテレワークをするために、予めどのようなことを決めておいたらよいか、どういった進め方をしたらよいか、どんなツールを使ったらよいかなどを解説しています。"
image: title.webp
draft: false
---
<div id='product-component-1627483918148'></div>
<script type="text/javascript">
/*<![CDATA[*/
(function () {
  var scriptURL = 'https://sdks.shopifycdn.com/buy-button/latest/buy-button-storefront.min.js';
  if (window.ShopifyBuy) {
    if (window.ShopifyBuy.UI) {
      ShopifyBuyInit();
    } else {
      loadScript();
    }
  } else {
    loadScript();
  }
  function loadScript() {
    var script = document.createElement('script');
    script.async = true;
    script.src = scriptURL;
    (document.getElementsByTagName('head')[0] || document.getElementsByTagName('body')[0]).appendChild(script);
    script.onload = ShopifyBuyInit;
  }
  function ShopifyBuyInit() {
    var client = ShopifyBuy.buildClient({
      domain: 'linkup-works.myshopify.com',
      storefrontAccessToken: '891d1bc551076823c13d9e19798a6bce',
    });
    ShopifyBuy.UI.onReady(client).then(function (ui) {
      ui.createComponent('product', {
        id: '6905168462006',
        node: document.getElementById('product-component-1627483918148'),
        moneyFormat: '%C2%A5%7B%7Bamount_no_decimals%7D%7D',
        options: {
  "product": {
    "styles": {
      "product": {
        "@media (min-width: 601px)": {
          "max-width": "100%",
          "margin-left": "0",
          "margin-bottom": "50px"
        },
        "text-align": "left"
      },
      "title": {
        "font-size": "26px"
      },
      "button": {
        ":hover": {
          "background-color": "#28a2cf"
        },
        "background-color": "#2cb4e6",
        ":focus": {
          "background-color": "#28a2cf"
        },
        "border-radius": "7px"
      },
      "price": {
        "font-size": "18px"
      },
      "compareAt": {
        "font-size": "15.299999999999999px"
      },
      "unitPrice": {
        "font-size": "15.299999999999999px"
      }
    },
    "buttonDestination": "checkout",
    "layout": "horizontal",
    "contents": {
      "img": false,
      "imgWithCarousel": true,
      "description": true
    },
    "width": "100%",
    "text": {
      "button": "購入する"
    }
  },
  "productSet": {
    "styles": {
      "products": {
        "@media (min-width: 601px)": {
          "margin-left": "-20px"
        }
      }
    }
  },
  "modalProduct": {
    "contents": {
      "img": false,
      "imgWithCarousel": true,
      "button": false,
      "buttonWithQuantity": true
    },
    "styles": {
      "product": {
        "@media (min-width: 601px)": {
          "max-width": "100%",
          "margin-left": "0px",
          "margin-bottom": "0px"
        }
      },
      "button": {
        ":hover": {
          "background-color": "#28a2cf"
        },
        "background-color": "#2cb4e6",
        ":focus": {
          "background-color": "#28a2cf"
        },
        "border-radius": "7px"
      },
      "title": {
        "font-family": "Helvetica Neue, sans-serif",
        "font-weight": "bold",
        "font-size": "26px",
        "color": "#4c4c4c"
      },
      "price": {
        "font-family": "Helvetica Neue, sans-serif",
        "font-weight": "normal",
        "font-size": "18px",
        "color": "#4c4c4c"
      },
      "compareAt": {
        "font-family": "Helvetica Neue, sans-serif",
        "font-weight": "normal",
        "font-size": "15.299999999999999px",
        "color": "#4c4c4c"
      },
      "unitPrice": {
        "font-family": "Helvetica Neue, sans-serif",
        "font-weight": "normal",
        "font-size": "15.299999999999999px",
        "color": "#4c4c4c"
      }
    },
    "text": {
      "button": "Add to cart"
    }
  },
  "option": {},
  "cart": {
    "styles": {
      "button": {
        ":hover": {
          "background-color": "#28a2cf"
        },
        "background-color": "#2cb4e6",
        ":focus": {
          "background-color": "#28a2cf"
        },
        "border-radius": "7px"
      }
    },
    "text": {
      "total": "Subtotal",
      "button": "Checkout"
    },
    "popup": false
  },
  "toggle": {
    "styles": {
      "toggle": {
        "background-color": "#2cb4e6",
        ":hover": {
          "background-color": "#28a2cf"
        },
        ":focus": {
          "background-color": "#28a2cf"
        }
      }
    }
  }
},
      });
    });
  }
})();
/*]]>*/
</script>