# Price Card Project.

```HTML
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
    <link rel="stylesheet" href="./assets/css/bootstrap.min.css" />
    <link rel="stylesheet" href="./assets/css/style.css" />
    <title>Pricing Cards</title><!-- change title -->
  </head>
  <body>
    <div class="container">

      <div class="row mt-5">

        <div class="col-md-6">

          <!-- Card 1 -->
          <div class="card rounded-4 shadow-lg border-0 mb5">

            <div class="card-body">
              <div>
                <h4 class="fw-bold">Free</h4><!-- End 1st h4 heading -->
                <p class="text-muted">
                  For Freelancers
                </p><!-- End text-muted lass --> 
              </div><!-- End div h4 container -->

              <h2 class="fs-1 fw-bold mt-4 mb-5">$0</h2><!-- End h2 heading -->
              <ul class="list-group list-group flush fs-5 mb-5 vstack gap-3">

                <li class="list-group-item border-0">
                  <i class="bi bi-check2"></i> Single User
                </li><!-- End 1st li with list-group-item class-->

                <li class="list-group-item border-0">
                  <i class="bi bi-check2"></i> 10 Downloads Per Month
                </li><!-- End 2nd li with list-group-item class-->

                <li class="list-group-item border-0">
                  <i class="bi bi-check2"></i> Faster Files
                </li><!-- End 3rd li with list-group-item class-->

                <li class="list-group-item border-0">
                  <i class="bi bi-check2"></i> 25 Custom Packs
                </li><!-- End 4th li with list-group-item class-->

              </ul><!-- End ul 1st card -->
              <div class="d-grid">
                <button class="btn btn-dark rounded-4 mt-5 mb-4">Subscribe

                </button><!-- End Button element -->
              </div><!-- End button container -->
            </div><!-- end card body class -->
          </div><!-- End 1st card -->
        </div><!-- End 1st column -->

        <div class="col-md-6">

          <!-- Card 2 -->
          <div class="card text-bg-dark rounded-4 shadow-lg border-0 mb5">

            <div class="card-body">
              <div>
                <h4 class="fw-bold">Pro</h4><!-- End 2nd h4 heading -->
                <p class="text-white">
                  For Agencies
                </p><!-- End text-white class --> 
              </div><!-- End div h4 container -->

              <h2 class="fs-1 fw-bold mt-4 mb-5">$100</h2><!-- End h2 heading -->
              <ul class="list-group list-group flush fs-5 mb-5 vstack gap-3">

                <li class="list-group-item border-0 text-bg-dark">
                  <i class="bi bi-check2"></i> Unlimited Users
                </li><!-- End 1st li with list-group-item class-->

                <li class="list-group-item border-0 text-bg-dark">
                  <i class="bi bi-check2"></i> Unlimited Downloads
                </li><!-- End 2nd li with list-group-item class-->

                <li class="list-group-item border-0 text-bg-dark">
                  <i class="bi bi-check2"></i> Fully Editable Files
                </li><!-- End 3rd li with list-group-item class-->

                <li class="list-group-item border-0 text-bg-dark">
                  <i class="bi bi-check2"></i> 200+ Custom Packs
                </li><!-- End 4th li with list-group-item class-->

              </ul><!-- End ul 2nd card -->
              <div class="d-grid">
                <button class="btn btn-light rounded-4 mt-5 mb-4">Subscribe

                </button><!-- End Button element -->
              </div><!-- End button container -->
            </div><!-- end card body class -->
          </div><!-- End 2nd card -->
        </div><!-- End 2nd column -->

    <script src="./assets/js/bootstrap.bundle.min.js"></script>
  </body>
</html>
<!-- Step 1:  add a container(16) -->
<!-- Step 2:  create a row inside the container(17) -->
<!-- Step 3:  add two columns(19) -->
<!-- Step 4:  add two cards(20) -->
<!-- Step 5:  add card-body class(20) -->
<!-- Step 6:  add h4 heading div container(26) -->
<!-- Step 7:  add fw-bold class(27) -->
<!-- Step 8:  add text-muted class(28) -->
<!-- Step 9:  add h2 with classes: fs-1, fw-bold, mt-4, mb-5(33) -->
<!-- Step 10: add unorganized list with list-group, list-group-flush, fs-5, mb-5(34) -->
<!-- Step 11: add li with list-group-item class(36)-->
<!-- Step 12: add bi bi-check2 class(37) -->
<!-- Step 13: copy Step 12 x3 below step 12 -->
<!-- Step 14: add border-0 class to step 12 -->
<!-- Step 15: add vstack gap-2 class to Step 10-->
<!-- Step 16: add d-grid class to div container for button(53)-->
<!-- Step 17: add button with btn btn-dark rounded-4 mt-5 mb-4 classes(54) -->
<!-- Step 18: add media query to style.css to fix cards' width -->
<!-- Step 19: add text-bg-dark to line 65 -->
<!-- Step 20: change text-muted for text-white class on line 70 -->
<!-- Step 21: add text-bg-dark on lines 78, 82, 86, 90 -->
<!-- Step 22: add btn btn-lign class to button on line -->
```
## style.css
```CSS
body{
    font-family: 'Poppins', sans-serif;
}

@media(min-width: 800px){
    .container{
        width: 800px;
    }
}
```