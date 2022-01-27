
Responsive Shopping Carts built with Bootstrap 5. Multiple examples of various designs and functionalities. Ready to use pages and templates.

Check out [Bootstrap Shopping Carts Documentation](https://mdbootstrap.com/docs/standard/extended/shopping-carts/) for detailed instructions & even more examples.

## Basic example

![Bootstrap 5 Shopping Carts](https://mdbootstrap.com/img/Marketing/github/shopping-carts/basic.png)

```html
<section class="h-100 h-custom" style="background-color: #eee;">
  <div class="container py-5 h-100">
    <div class="row d-flex justify-content-center align-items-center h-100">
      <div class="col">
        <div class="card">
          <div class="card-body p-4">

            <div class="row">

              <div class="col-lg-7">
                <h5 class="mb-3"><a href="#!" class="text-body"><i
                      class="fas fa-long-arrow-alt-left me-2"></i>Continue shopping</a></h5>
                <hr>

                <div class="d-flex justify-content-between align-items-center mb-4">
                  <div>
                    <p class="mb-1">Shopping cart</p>
                    <p class="mb-0">You have 4 items in your cart</p>
                  </div>
                  <div>
                    <p class="mb-0"><span class="text-muted">Sort by:</span> <a href="#!"
                        class="text-body">price <i class="fas fa-angle-down mt-1"></i></a></p>
                  </div>
                </div>

                <div class="card mb-3">
                  <div class="card-body">
                    <div class="d-flex justify-content-between">
                      <div class="d-flex flex-row align-items-center">
                        <div>
                          <img
                            src="https://mdbcdn.b-cdn.net/img/Photos/new-templates/bootstrap-shopping-carts/img1.webp"
                            class="img-fluid rounded-3" alt="Shopping item" style="width: 65px;">
                        </div>
                        <div class="ms-3">
                          <h5>Iphone 11 pro</h5>
                          <p class="small mb-0">256GB, Navy Blue</p>
                        </div>
                      </div>
                      <div class="d-flex flex-row align-items-center">
                        <div style="width: 50px;">
                          <h5 class="fw-normal mb-0">2</h5>
                        </div>
                        <div style="width: 80px;">
                          <h5 class="mb-0">$900</h5>
                        </div>
                        <a href="#!" style="color: #cecece;"><i class="fas fa-trash-alt"></i></a>
                      </div>
                    </div>
                  </div>
                </div>

                <div class="card mb-3">
                  <div class="card-body">
                    <div class="d-flex justify-content-between">
                      <div class="d-flex flex-row align-items-center">
                        <div>
                          <img
                            src="https://mdbcdn.b-cdn.net/img/Photos/new-templates/bootstrap-shopping-carts/img2.webp"
                            class="img-fluid rounded-3" alt="Shopping item" style="width: 65px;">
                        </div>
                        <div class="ms-3">
                          <h5>Samsung galaxy Note 10 </h5>
                          <p class="small mb-0">256GB, Navy Blue</p>
                        </div>
                      </div>
                      <div class="d-flex flex-row align-items-center">
                        <div style="width: 50px;">
                          <h5 class="fw-normal mb-0">2</h5>
                        </div>
                        <div style="width: 80px;">
                          <h5 class="mb-0">$900</h5>
                        </div>
                        <a href="#!" style="color: #cecece;"><i class="fas fa-trash-alt"></i></a>
                      </div>
                    </div>
                  </div>
                </div>

                <div class="card mb-3">
                  <div class="card-body">
                    <div class="d-flex justify-content-between">
                      <div class="d-flex flex-row align-items-center">
                        <div>
                          <img
                            src="https://mdbcdn.b-cdn.net/img/Photos/new-templates/bootstrap-shopping-carts/img3.webp"
                            class="img-fluid rounded-3" alt="Shopping item" style="width: 65px;">
                        </div>
                        <div class="ms-3">
                          <h5>Canon EOS M50</h5>
                          <p class="small mb-0">Onyx Black</p>
                        </div>
                      </div>
                      <div class="d-flex flex-row align-items-center">
                        <div style="width: 50px;">
                          <h5 class="fw-normal mb-0">1</h5>
                        </div>
                        <div style="width: 80px;">
                          <h5 class="mb-0">$1199</h5>
                        </div>
                        <a href="#!" style="color: #cecece;"><i class="fas fa-trash-alt"></i></a>
                      </div>
                    </div>
                  </div>
                </div>

                <div class="card mb-3 mb-lg-0">
                  <div class="card-body">
                    <div class="d-flex justify-content-between">
                      <div class="d-flex flex-row align-items-center">
                        <div>
                          <img
                            src="https://mdbcdn.b-cdn.net/img/Photos/new-templates/bootstrap-shopping-carts/img4.webp"
                            class="img-fluid rounded-3" alt="Shopping item" style="width: 65px;">
                        </div>
                        <div class="ms-3">
                          <h5>MacBook Pro</h5>
                          <p class="small mb-0">1TB, Graphite</p>
                        </div>
                      </div>
                      <div class="d-flex flex-row align-items-center">
                        <div style="width: 50px;">
                          <h5 class="fw-normal mb-0">1</h5>
                        </div>
                        <div style="width: 80px;">
                          <h5 class="mb-0">$1799</h5>
                        </div>
                        <a href="#!" style="color: #cecece;"><i class="fas fa-trash-alt"></i></a>
                      </div>
                    </div>
                  </div>
                </div>

              </div>
              <div class="col-lg-5">

                <div class="card bg-primary text-white rounded-3">
                  <div class="card-body">
                    <div class="d-flex justify-content-between align-items-center mb-4">
                      <h5 class="mb-0">Card details</h5>
                      <img src="https://mdbcdn.b-cdn.net/img/Photos/Avatars/avatar-6.webp"
                        class="img-fluid rounded-3" style="width: 45px;" alt="Avatar">
                    </div>

                    <p class="small mb-2">Card type</p>
                    <a href="#!" type="submit" class="text-white"><i
                        class="fab fa-cc-mastercard fa-2x me-2"></i></a>
                    <a href="#!" type="submit" class="text-white"><i
                        class="fab fa-cc-visa fa-2x me-2"></i></a>
                    <a href="#!" type="submit" class="text-white"><i
                        class="fab fa-cc-amex fa-2x me-2"></i></a>
                    <a href="#!" type="submit" class="text-white"><i class="fab fa-cc-paypal fa-2x"></i></a>

                    <form class="mt-4">
                      <div class="form-outline form-white mb-4">
                        <input type="text" id="typeName" class="form-control form-control-lg" siez="17"
                          placeholder="Cardholder's Name" />
                        <label class="form-label" for="typeName">Cardholder's Name</label>
                      </div>

                      <div class="form-outline form-white mb-4">
                        <input type="text" id="typeText" class="form-control form-control-lg" siez="17"
                          placeholder="1234 5678 9012 3457" minlength="19" maxlength="19" />
                        <label class="form-label" for="typeText">Card Number</label>
                      </div>

                      <div class="row mb-4">
                        <div class="col-md-6">
                          <div class="form-outline form-white">
                            <input type="text" id="typeExp" class="form-control form-control-lg"
                              placeholder="MM/YYYY" size="7" id="exp" minlength="7" maxlength="7" />
                            <label class="form-label" for="typeExp">Expiration</label>
                          </div>
                        </div>
                        <div class="col-md-6">
                          <div class="form-outline form-white">
                            <input type="password" id="typeText" class="form-control form-control-lg"
                              placeholder="&#9679;&#9679;&#9679;" size="1" minlength="3" maxlength="3" />
                            <label class="form-label" for="typeText">Cvv</label>
                          </div>
                        </div>
                      </div>

                    </form>

                    <hr class="my-4">

                    <div class="d-flex justify-content-between">
                      <p class="mb-2">Subtotal</p>
                      <p class="mb-2">$4798.00</p>
                    </div>

                    <div class="d-flex justify-content-between">
                      <p class="mb-2">Shipping</p>
                      <p class="mb-2">$20.00</p>
                    </div>

                    <div class="d-flex justify-content-between mb-4">
                      <p class="mb-2">Total(Incl. taxes)</p>
                      <p class="mb-2">$4818.00</p>
                    </div>

                    <button type="button" class="btn btn-info btn-block btn-lg">
                      <div class="d-flex justify-content-between">
                        <span>$4818.00</span>
                        <span>Checkout <i class="fas fa-long-arrow-alt-right ms-2"></i></span>
                      </div>
                    </button>

                  </div>
                </div>

              </div>

            </div>

          </div>
        </div>
      </div>
    </div>
  </div>
</section>
```

```css
@media (min-width: 1025px) {
.h-custom {
height: 100vh !important;
}
}
```

## How to use?

1. Download MDB 5 - free UI KIT

2. Choose your favourite customized component and click on the image

3. Copy & paste the code into your MDB project

[▶️ Subscribe to YouTube channel for web development tutorials & resources](https://www.youtube.com/MDBootstrap?sub_confirmation=1)

## More examples

[Bootstrap Shopping carts #2:
![Bootstrap 5 Shopping Carts](https://mdbootstrap.com/img/Marketing/github/shopping-carts/section-2.png)](https://mdbootstrap.com/docs/standard/extended/shopping-carts/#section-2)

[Bootstrap Shopping carts #3:
![Bootstrap 5 Shopping Carts](https://mdbootstrap.com/img/Marketing/github/shopping-carts/section-3.png)](https://mdbootstrap.com/docs/standard/extended/shopping-carts/#section-3)

[Bootstrap Shopping carts #4:
![Bootstrap 5 Shopping Carts](https://mdbootstrap.com/img/Marketing/github/shopping-carts/section-4.png)](https://mdbootstrap.com/docs/standard/extended/shopping-carts/#section-4)

[Bootstrap Shopping carts #5:
![Bootstrap 5 Shopping Carts](https://mdbootstrap.com/img/Marketing/github/shopping-carts/section-5.png)](https://mdbootstrap.com/docs/standard/extended/shopping-carts/#section-5)

[Bootstrap Shopping carts #6:
![Bootstrap 5 Shopping Carts](https://mdbootstrap.com/img/Marketing/github/shopping-carts/section-6.png)](https://mdbootstrap.com/docs/standard/extended/shopping-carts/#section-6)

[Bootstrap Shopping carts #7:
![Bootstrap 5 Shopping Carts](https://mdbootstrap.com/img/Marketing/github/shopping-carts/section-7.png)](https://mdbootstrap.com/docs/standard/extended/shopping-carts/#section-7)

___

## More extended Bootstrap documentation

<ul>
<li><a href="https://mdbootstrap.com/docs/standard/extended/bootstrap-address-form/">Bootstrap Address Form</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/avatar/">Bootstrap Avatar</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/back-to-top/">Bootstrap Back To Top Button</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/carousel-with-thumbnails/">Bootstrap Carousel Slider with Thumbnails</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/chat/">Bootstrap Chat</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/code/">Bootstrap Code Blocks</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/comments/">Bootstrap Comments</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/bootstrap-comparison-table/">Bootstrap Comparison Table</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/credit-card/">Bootstrap Credit Card Form</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/drawer/">Bootstrap Drawer</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/dropdown-multilevel/">Bootstrap Nested Dropdown</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/faq/">Bootstrap FAQ component / section</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/gallery/">Bootstrap Gallery</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/hamburger-menu/">Bootstrap Hamburger Menu</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/bootstrap-invoice/">Bootstrap Invoice</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/jumbotron/">Bootstrap Jumbotron</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/login/">Bootstrap Login Form</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/maps/">Bootstrap Maps</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/media-object/">Bootstrap Media Object</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/mega-menu/">Bootstrap Mega Menu</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/multiselect/">Bootstrap Multiselect</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/news-feed/">Bootstrap News Feed</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/offcanvas/">Bootstrap Offcanvas</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/order-details/">Bootstrap Order Details</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/page-transitions/">Bootstrap Page Transitions</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/payment-forms/">Bootstrap Payment Forms</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/product-cards/">Bootstrap Product Cards</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/profiles/">Bootstrap Profiles</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/quotes/">Bootstrap Quotes</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/registration/">Bootstrap Registration Form</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/search-expanding/">Bootstrap Expanding Search Bar</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/shopping-carts/">Bootstrap Shopping Carts</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/side-navbar/">Bootstrap Side Navbar</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/sidebar/">Bootstrap Sidebar</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/social-media/">Bootstrap Social Media Icons & Buttons</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/square-buttons/">Bootstrap Square Buttons</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/bootstrap-survey-form/">Bootstrap Survey Form</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/testimonial-slider/">Bootstrap Testimonial Slider</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/testimonials/">Bootstrap Testimonials</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/textarea/">Bootstrap Textarea</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/timeline/">Bootstrap Timeline</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/to-do-list/">Bootstrap To Do List</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/video-carousel/">Bootstrap Video Carousel / Gallery</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/weather/">Bootstrap Weather</a></li>  
</ul>

