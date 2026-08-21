function initReviewsSlider(){
 var uswiper = new Swiper(".umySwiper", {
    loop:true,
    slidesPerView: 4,
    spaceBetween: 25,
    navigation: {
      nextEl: ".swiper-button-next",
      prevEl: ".swiper-button-prev",
    },
    breakpoints: {
      348: {
        slidesPerView: 2,
        spaceBetween: 20,
        navigation:false
      },
      640: {
        slidesPerView: 4,
        spaceBetween: 25,
      }
    }
  });
}

document.addEventListener('DOMContentLoaded', (event) => {
    var coll = document.getElementsByClassName("collapsibleuz");
    for (var i = 0; i < coll.length; i++) {
        coll[i].addEventListener("click", function() {
            this.classList.toggle("active");
            var content = this.nextElementSibling;
            if (content.style.maxHeight) {
                content.style.maxHeight = null;
            } else {
                content.style.maxHeight = content.scrollHeight + "px";
            }
            
            var plusMinus = this.querySelector('.plusminus');
            if (plusMinus) {
                plusMinus.classList.toggle('active');
            }
        });
    }
});

function reviewsinitializeSwiper() {
  var swiper = new Swiper(".u-reviews-umySwiper", {
    spaceBetween: 30,
    loop:true,
    navigation: {
      nextEl: ".swiper-button-next",
      prevEl: ".swiper-button-prev",
    },
    breakpoints: {
      348: {
        centeredSlides: true,
        slidesPerView: 1.2,
        spaceBetween: 20,
        centeredSlidesBounds: true,
      },
      640: {
        slidesPerView: 2.2,
        spaceBetween: 20,
      },
      768: {
        slidesPerView: 2.6,
        spaceBetween: 30,
      },
      1024: {
        slidesPerView: 3.25,
        spaceBetween: 30,
      }
    }
  });
}

reviewsinitializeSwiper();

function checkVisibilitybtn() {
  let stickyatc = document.querySelector("#u-back-to-top");
  if (window.scrollY > window.innerHeight) {
    stickyatc.classList.add("uvisible");
  } else {
    stickyatc.classList.remove("uvisible");
  }
}

document.querySelector("#u-back-to-top")?.addEventListener("click", function(e) {
  let ogproductform = document.querySelector(".u-marquee-wrapper");
  if (ogproductform) {
    ogproductform.scrollIntoView({
      behavior: "smooth",
      block: "start"
    });
  }
});

window.addEventListener("scroll", checkVisibilitybtn);
window.addEventListener("resize", checkVisibilitybtn);
checkVisibilitybtn();

function checkVisibility() {
  let ogPaymentElement = document.querySelector(".og-payment");
  let stickyatc = document.querySelector("#cstm-sticky-bar");
  if (isElementMovedUpAndOutOfViewport(ogPaymentElement)) {
      stickyatc.classList.add("mvisible");
  } else {
      stickyatc.classList.remove("mvisible");
  }
}  
window.addEventListener("scroll", checkVisibility);
window.addEventListener("resize", checkVisibility); // Listen for window resize
checkVisibility();

function updatePriceNimageSticky(){
  var getData = document.querySelector('div#cstm-sticky-bar select.matc-variantsSelecter').selectedOptions[0].dataset;
  var image = getData.image;
  var price = getData.price;
  var cprice = getData.cprice;
  
if(document.querySelector('div#cstm-sticky-bar img.sticky-bar-thumb-thumb'))
document.querySelector('div#cstm-sticky-bar img.sticky-bar-thumb-thumb').src= image;
  
if(document.querySelector('div#cstm-sticky-bar span.matc-price'))
document.querySelector('div#cstm-sticky-bar span.matc-price').innerHTML= price;
 
if(document.querySelector('div#cstm-sticky-bar span.matc-compare-price'))
document.querySelector('div#cstm-sticky-bar span.matc-compare-price').innerHTML= cprice;
}

function addToCartStickyBar() {
  const formData = {
    quantity: parseInt(
      document.querySelector('.matc-form input[name="quantity"]')?.value
    ) || 1,
    id: parseInt(
      document.querySelector('#matc-variantsSelect')?.value
    )
  };

  fetch(window.Shopify.routes.root + 'cart/add.js', {
    method: 'POST',
    headers: {
      'Content-Type': 'application/json',
    },
    body: JSON.stringify(formData)
  })
  .then((response) => response.json())
  .then((product) => {
    // Fetch updated cart to get full cart data
    return fetch(window.Shopify.routes.root + 'cart.js')
      .then(res => res.json())
      .then(cart => {
        // Update and open AMP Slide Cart
        if (window.SLIDECART_UPDATE) {
          window.SLIDECART_UPDATE(cart);
        }
        if (window.SLIDECART_OPEN) {
          window.SLIDECART_OPEN();
        }
        
        // Hide sticky bar
        document
          .getElementById('cstm-sticky-bar')
          ?.classList.remove('mvisible');
      });
  })
  .catch((e) => {
    console.error('Add to cart failed:', e);
  });
}

// HIDE ON FOOTER VISIBLE

function isElementMovedUpAndOutOfViewport(el) {
  var rect = el.getBoundingClientRect();
  return (
      rect.bottom <= 0 &&
      rect.top < window.innerHeight
  );
}

function isElementInViewport(el) {
  var rect = el.getBoundingClientRect();
  return (
      rect.top < window.innerHeight &&
      rect.bottom > 0
  );
}

function checkVisibility() {
  let ogPaymentElement = document.querySelector(".og-payment");
  let stickyatc = document.querySelector("#cstm-sticky-bar");
  let footer = document.querySelector("footer");

  // If footer is visible, undo everything
  if (isElementInViewport(footer)) {
      stickyatc.classList.remove("mvisible");
      return; // Exit the function if footer is visible
  }

  // Check if the payment element is out of the viewport
  if (isElementMovedUpAndOutOfViewport(ogPaymentElement)) {
      stickyatc.classList.add("mvisible");
  } else {
      stickyatc.classList.remove("mvisible");
  }
}  

window.addEventListener("scroll", checkVisibility);
window.addEventListener("resize", checkVisibility); // Listen for window resize
checkVisibility();