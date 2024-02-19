# Ratings Component Project.

```HTML
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" integrity="sha512-DTOQO9RWCH3ppGqcWaEA1BIZOC6xxalwEsw9c2QQeAIftl+Vegovlnee1c9QX4TctnWMn13TZye+giMm8e2LwA==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="stylesheet" href="./css/bootstrap.min.css" />
    <link rel="stylesheet" href="./css/style.css" />
    <title>Ratings Components</title><!-- change title -->
  </head>
  <body>

    <div class="container mt-5">

      <div class="card">
        <div class="card-body">
          <div class="row p-5">
            <div class="col-7">
              <h2 class="fw-bold">What others think about the product.</h2>
            </div><!-- End col-7 -->

            <div class="col-5">
              <div class="card">
                <div class="card-body">
                  <h3 class="display-5 fw-semibold">
                    <i class="fas fa-star text-warning"></i> 4.8
                  </h3><!-- End h3 -->
                  <p class="text-center">Average Rating</p>
                </div><!-- End card-body -->
              </div><!-- End card 2 -->
            </div><!-- End col-5 -->
          </div><!-- End row header(sorta) -->

          <!-- Search -->
          <div class="row px-5">
            <div class="col-12">
              <div class="input-group input-group-lg">
                <span class="input-group-text rounded-start-5">
                  <i class="fas fa-search"></i>
                </span><!-- End input-group-text -->
                <input type="text" class="form-control rounded-end-5" placeholder="Search Reviews">
              </div><!-- End input group -->
            </div><!-- End col-12 -->
          </div><!-- End row search bar -->

          <!-- Ratings -->
          <div class="row p-5">
            <div class="col-12 vstack gap-2">
              <h5>Ratings</h5>
              <div class="d-flex align-items-center gap-1">
                <span>5</span> <i class="fas fa-star text-warning"></i>
                <div class="progress ms-3" style="height: 10px; width: 100%;">
                  <div class="progress-bar bg-warning" 
                  style="width: 80%;"
                  role="progressbar"
                  aria-valuenow="80"
                  aria-valuemin="0"
                  aria-valuemax="100"></div><!-- End progress bar fill-->
                </div><!-- progress div end -->
              </div><!-- d-flex end -->

              <div class="d-flex align-items-center gap-1">
                <span>4</span> <i class="fas fa-star text-warning"></i>
                <div class="progress ms-3" style="height: 10px; width: 100%;">
                  <div class="progress-bar bg-warning" 
                  style="width: 60%;"
                  role="progressbar"
                  aria-valuenow="60"
                  aria-valuemin="0"
                  aria-valuemax="100"></div><!-- End progress bar fill-->
                </div><!-- progress div end -->
              </div><!-- d-flex end -->

              <div class="d-flex align-items-center gap-1">
                <span>3</span> <i class="fas fa-star text-warning"></i>
                <div class="progress ms-3" style="height: 10px; width: 100%;">
                  <div class="progress-bar bg-warning" 
                  style="width: 20%;"
                  role="progressbar"
                  aria-valuenow="20"
                  aria-valuemin="0"
                  aria-valuemax="100"></div><!-- End progress bar fill-->
                </div><!-- progress div end -->
              </div><!-- d-flex end -->

              <div class="d-flex align-items-center gap-1">
                <span>2</span> <i class="fas fa-star text-warning"></i>
                <div class="progress ms-3" style="height: 10px; width: 100%;">
                  <div class="progress-bar bg-warning" 
                  style="width: 10%;"
                  role="progressbar"
                  aria-valuenow="10"
                  aria-valuemin="0"
                  aria-valuemax="100"></div><!-- End progress bar fill-->
                </div><!-- progress div end -->
              </div><!-- d-flex end -->

              <div class="d-flex align-items-center gap-1">
                <span>1</span> <i class="fas fa-star text-warning"></i>
                <div class="progress ms-3" style="height: 10px; width: 100%;">
                  <div class="progress-bar bg-warning" 
                  style="width: 30%;"
                  role="progressbar"
                  aria-valuenow="30"
                  aria-valuemin="0"
                  aria-valuemax="100"></div><!-- End progress bar fill-->
                </div><!-- progress div end -->
              </div><!-- d-flex end -->

            </div><!-- End col-12 -->
          </div><!-- end row ratings-->

          <!-- Button -->
          <div class="row px-5 pb-4">
            <div class="col-12">
              <a href="#" class="btn btn-success btn-lg rounded-5">Write Review</a>
            </div><!-- End col-12 -->
          </div><!-- End button row -->
          
        </div><!-- End card body -->
      </div><!--End card div -->     
    </div><!-- End div container -->

    <script src="./assets/js/bootstrap.bundle.min.js"></script>
  </body>
</html>

<!-- Step 1: Change title on line 12 -->
<!-- Step 2: add font awesome cdn on line 7 -->
<!-- Step 3: add container on line 13 -->
<!-- Step 4: add div card on line 14 -->
<!-- Step 5: add div card-body on line 15 -->
<!-- Step 6: add row with padding on line 16 -->
<!-- Step 7: add column on line 17 -->
<!-- Step 8: add h2 with fw-bold class line 18 -->
<!-- Step 9: add column on line 20  -->
<!-- Step 10: add card class on line 21  -->
<!-- Step 11: add card-body on line 22 -->
<!-- Step 12: add h3 with display-5 fw-semibold classes on line 23 -->
<!-- Step 13: add i tag with fas fa-star text-warning classes on line 24 -->
<!-- Step 14: add p tag with text-center class on line 26 -->
<!-- Step 15: add search bar under 1st row on line -->
<!-- Step 16: add row with class row and px-5 on line 36 -->
<!-- Step 17: add col-12 on line 37 -->
<!-- Step 18: add input group on line 38 -->
<!-- Step 19: add input-group-text on line 39 -->
<!-- Step 20: add search icon on line 40 -->
<!-- Step 21: add- input with from control on line 42 -->
<!-- Step 22: add row on line 48 -->
<!-- Step 23: add col-12 with vstack gap-2 on line 49 -->
<!-- Step 24: add h5 on line 50 -->
<!-- Step 25: add d-flex class on line 51 -->
<!-- Step 26: add span #5 with icon on line 52 -->
<!-- Step 27: add progress class on line -->
<!-- Step 28: add progress-bar class on line 54 -->
<!-- Step 29: add button row on line 115 -->
<!-- Step 30: add col-12 on line 116 -->
<!-- Step 31: add link button on line 117 -->
```
