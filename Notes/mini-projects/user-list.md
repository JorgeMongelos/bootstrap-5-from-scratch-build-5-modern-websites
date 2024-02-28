# User List Mini Project.

```HTML
<!DOCTYPE html>
<html lang="en" data-bs-theme="dark">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="./css/bootstrap.min.css" />
    <link rel="stylesheet" href="./css/style.css" />
    <title>User List</title>
  </head>
  <body>

    <header class="mb-5">
      <div class="container mt-5">
        <div class="d-flex justify-content-end">
          <div class="btn-group">
            <button class="btn btn-secondary btn-sm" data-bs-theme-value="dark">
              Dark
            </button><!-- btn end -->
            <button class="btn btn-light btn-sm" data-bs-theme-value="light">
              Light
            </button><!-- btn end -->
          </div><!-- btn-group end -->
        </div><!-- d-flex end -->

        <h1 class="mb-4">Users</h1>
        <div class="row">
          <div class="col-md-4">
            <input type="text" class="form-control form-control-lg" placeholder="Search Users">
          </div><!-- end-col-md-4 -->   
          
          <div class="col-md-8 user-menu d-flex justify-content-end alight-items-center">
            <ul class="nav">

              <li class="nav-item">
                <a href="#" class="nav-link">Reputation</a><!-- End nav link -->
              </li><!-- end li nav-item -->
              <li class="nav-item">
                <a href="#" class="nav-link text-bg-primary rounded-3">New Users</a><!-- End nav link -->
              </li><!-- end li nav-item -->
              <li class="nav-item">
                <a href="#" class="nav-link">Editors</a><!-- End nav link -->
              </li><!-- end li nav-item -->
              <li class="nav-item">
                <a href="#" class="nav-link">Moderators</a><!-- End nav link -->
              </li><!-- end li nav-item -->

            </ul><!-- End ul nav -->
          </div><!-- col-md-8 end -->
        </div><!-- End row -->

      </div><!-- End container  -->
    </header><!-- End header -->

    <!-- User List -->
    <main>

      <div class="container">

        <div class="row">

          <div class="col-md-4">

            <div class="card mb-3" data-bs-container="body" data-bs-toggle="popover" data-bs-placement="top" data-bs-content="Email: john@gmail.com">

              <div class="card-body">

                <div class="d-flex gap-3">

                  <img src="https://randomuser.me/api/portraits/men/75.jpg" alt="" class="img-fluid rounded-circle">
                  <div class="user-info">
                    <h4>John Doe</h4>
                    <h6>Troy MI</h6>
                    <span class="badge bg-primary">Nature</span>
                    <span class="badge bg-primary">Travel</span>
                    <span class="badge bg-primary">Sports</span>
                  
                  </div><!-- End user-info  -->
                
                </div><!-- End d-flex -->

              </div><!-- End card-body-->

            </div><!-- End card -->

          </div><!-- End col-md-4 -->

          <div class="col-md-4">

            <div class="card mb-3" data-bs-container="body" data-bs-toggle="popover" data-bs-placement="top" data-bs-content="Email: lelah@gmail.com">

              <div class="card-body">

                <div class="d-flex gap-3">

                  <img src="https://randomuser.me/api/portraits/women/75.jpg" alt="" class="img-fluid rounded-circle">
                  <div class="user-info">
                    <h4>Lelah Nichols</h4>
                    <h6>Fort Worth, TX</h6>
                    <span class="badge bg-primary">Fashion</span>
                    <span class="badge bg-primary">STEM</span>
                    <span class="badge bg-primary">Architecture</span>
                  
                  </div><!-- End user-info  -->
                
                </div><!-- End d-flex -->

              </div><!-- End card-body-->

            </div><!-- End card -->

          </div><!-- End col-md-4 -->

          <div class="col-md-4">

            <div class="card mb-3" data-bs-container="body" data-bs-toggle="popover" data-bs-placement="top" data-bs-content="Email: annie@gmail.com">

              <div class="card-body">

                <div class="d-flex gap-3">

                  <img src="https://randomuser.me/api/portraits/women/50.jpg" alt="" class="img-fluid rounded-circle">
                  <div class="user-info">
                    <h4>Annie Rice</h4>
                    <h6>Troy MI</h6>
                    <span class="badge bg-primary">Electronics</span>
                    <span class="badge bg-primary">Tech</span>
                    <span class="badge bg-primary">Music</span>
                  
                  </div><!-- End user-info  -->
                
                </div><!-- End d-flex -->

              </div><!-- End card-body-->

            </div><!-- End card -->

          </div><!-- End col-md-4 -->
          
        </div><!-- End row -->

        <div class="row">

          <div class="col-md-4">

            <div class="card mb-3" data-bs-container="body" data-bs-toggle="popover" data-bs-placement="top" data-bs-content="Email: thomas@gmail.com">

              <div class="card-body">

                <div class="d-flex gap-3">

                  <img src="https://randomuser.me/api/portraits/men/15.jpg" alt="" class="img-fluid rounded-circle">
                  <div class="user-info">
                    <h4>Thomas Sinew</h4>
                    <h6>Lynn, MA</h6>
                    <span class="badge bg-primary">Vintage</span>
                    <span class="badge bg-primary">Clothing</span>
                    <span class="badge bg-primary">Sports</span>
                  
                  </div><!-- End user-info  -->
                
                </div><!-- End d-flex -->

              </div><!-- End card-body-->

            </div><!-- End card -->

          </div><!-- End col-md-4 -->

          <div class="col-md-4">

            <div class="card mb-3" data-bs-container="body" data-bs-toggle="popover" data-bs-placement="top" data-bs-content="Email: brianna@gmail.com">

              <div class="card-body">

                <div class="d-flex gap-3">

                  <img src="https://randomuser.me/api/portraits/women/10.jpg" alt="" class="img-fluid rounded-circle">
                  <div class="user-info">
                    <h4>Brianna Haylee</h4>
                    <h6>Boston, MA</h6>
                    <span class="badge bg-primary">Software</span>
                    <span class="badge bg-primary">Desing</span>
                    <span class="badge bg-primary">UI/UX</span>
                  
                  </div><!-- End user-info  -->
                
                </div><!-- End d-flex -->

              </div><!-- End card-body-->

            </div><!-- End card -->

          </div><!-- End col-md-4 -->

          <div class="col-md-4">

            <div class="card mb-3" data-bs-container="body" data-bs-toggle="popover" data-bs-placement="top" data-bs-content="Email: james@gmail.com">

              <div class="card-body">

                <div class="d-flex gap-3">

                  <img src="https://randomuser.me/api/portraits/men/40.jpg" alt="" class="img-fluid rounded-circle">
                  <div class="user-info">
                    <h4>James </h4>
                    <h6>Troy MI</h6>
                    <span class="badge bg-primary">Dance</span>
                    <span class="badge bg-primary">Fashion</span>
                    <span class="badge bg-primary">Music</span>
                  
                  </div><!-- End user-info  -->
                
                </div><!-- End d-flex -->

              </div><!-- End card-body-->

            </div><!-- End card -->

          </div><!-- End col-md-4 -->
          
        </div><!-- End row -->

      </div><!-- End container -->

    </main><!-- End main -->
    

    <script src="./js/bootstrap.bundle.min.js"></script>
    <script src="./js/darkmodetoggle.js"></script>
    <script>
      // const popoverEl = document.getElementById('popover');
      // const popover = new bootstrap.Popover(popoverEl);

      const popoverTriggerList = document.querySelectorAll(
        '[data-bs-toggle="popover"]'
      );

      const popoverList = [...popoverTriggerList].map(
        (popoverTriggerEl) => new bootstrap.Popover(popoverTriggerEl)
      );
    </script>
  </body>
</html>

<!-- Step 1: Change title on line 7 -->
<!-- Step 2: add header on line 11 -->
<!-- Step 3: add container on line 12 -->
<!-- Step 4: add d-flex on line 13-->
<!-- Step 5: add btn-group on line 14 -->
<!-- Step 6: add button on line 15 -->
<!-- Step 7: add h1 on line 25 -->
<!-- Step 8: add row on line 26 -->
<!-- Step 9: add col-md-4 on line 27 -->
<!-- Step 10: add input on line 28 -->
<!-- Step 11: add col-md-8 on line 31 -->
<!-- Step 12: add add navbar on line 32 -->
<!-- Step 13: add nav-item on line 33 -->
<!-- Step 14: add text-bg-primary rounded-3 on line 38 -->
<!-- Step 15: add media query in style.css -->
<!-- Step 16: add main tag on line 56 -->
<!-- Step 17: add container on line 57 -->
<!-- Step 18: add row on line 58 -->
<!-- Step 19: add col-md-4 on line 59 -->
<!-- Step 20: add card on line 60 -->
<!-- Step 21: add card-body on line 61 -->
<!-- Step 22: add d-flex on line 62 -->
<!-- Step 23: add dynamic image on line 63 -->
<!-- Step 24: add user-info on line 64 -->
<!-- Step 25: add h4 on line 65 -->
<!-- Step 26: add h6 on line 66-->
<!-- Step 27: add badge on line 70-->
```
