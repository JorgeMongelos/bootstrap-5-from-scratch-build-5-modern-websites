# Section 4: Dynamic JavaScript Components.
## Dropdowns
```HTML
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="./assets/css/bootstrap.min.css" />
    <title>Bootstrap Sandbox | Dropdowns</title>
  </head>
  <body>
    <div class="container">
      <h1 class="mb-5">Dropdowns</h1>

      <!-- Single Button -->
      <div class="dropdown">
        <button
          class="btn btn-primary dropdown-toggle"
          data-bs-toggle="dropdown"
        >
          Dropdown
        </button>
        <ul class="dropdown-menu">
          <li><a href="#" class="dropdown-item">Item 1</a></li>
          <li><a href="#" class="dropdown-item">Item 2</a></li>
          <li><a href="#" class="dropdown-item">Item 3</a></li>
        </ul>
      </div>

      <br /><br />

      <!-- Split Button -->
      <div class="btn-group">
        <button class="btn btn-danger">Action</button>
        <button
          class="btn btn-danger dropdown-toggle dropdown-toggle-split"
          data-bs-toggle="dropdown"
        >
          <span class="visually-hidden">Toggle Dropdown</span>
        </button>
        <ul class="dropdown-menu">
          <li><a href="#" class="dropdown-item">Item 1</a></li>
          <li><a href="#" class="dropdown-item">Item 2</a></li>
          <li><a href="#" class="dropdown-item">Item 3</a></li>
        </ul>
      </div>

      <br /><br />

      <!-- Dark Dropdowns -->
      <div class="dropdown">
        <button
          class="btn btn-primary dropdown-toggle"
          data-bs-toggle="dropdown"
        >
          Dropdown
        </button>
        <ul class="dropdown-menu dropdown-menu-dark">
          <li><a href="#" class="dropdown-item">Item 1</a></li>
          <li><a href="#" class="dropdown-item">Item 2</a></li>
          <li><a href="#" class="dropdown-item">Item 3</a></li>
        </ul>
      </div>

      <br /><br />

      <!-- Dropup -->
      <div class="btn-group dropup">
        <button class="btn btn-dark dropdown-toggle" data-bs-toggle="dropdown">
          Dropup
        </button>
        <ul class="dropdown-menu dropdown-menu-dark">
          <li><a href="#" class="dropdown-item">Item 1</a></li>
          <li><a href="#" class="dropdown-item">Item 2</a></li>
          <li><a href="#" class="dropdown-item">Item 3</a></li>
        </ul>
      </div>

      <br /><br />

      <!-- Navbar with Dropdown -->
      <nav class="navbar navbar-expand-md bg-light">
        <div class="container">
          <a href="#" class="navbar-brand">Navbar</a>
          <button
            type="button"
            data-bs-toggle="collapse"
            data-bs-target="#navbarNav"
            class="navbar-toggler"
          >
            <span class="navbar-toggler-icon"></span>
          </button>

          <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ms-auto">
              <li class="nav-item">
                <a href="#" class="nav-link active">Home</a>
              </li>
              <li class="nav-item">
                <a href="#about" class="nav-link">About</a>
              </li>
              <li class="nav-item">
                <a href="#" class="nav-link">Services</a>
              </li>
              <li class="nav-item">
                <a href="#" class="nav-link">Contact</a>
              </li>
              <li class="nav-item dropdown">
                <a
                  href="#"
                  class="nav-link dropdown-toggle"
                  data-bs-toggle="dropdown"
                  >Dropdown</a
                >
                <ul class="dropdown-menu">
                  <li><a href="#" class="dropdown-item">Item 1</a></li>
                  <li><a href="#" class="dropdown-item">Item 2</a></li>
                  <li><a href="#" class="dropdown-item">Item 3</a></li>
                </ul>
              </li>
            </ul>
          </div>
        </div>
      </nav>

      <!-- Don't go past here -->
    </div>
    <div style="margin-top: 350px"></div>

    <script src="./assets/js/bootstrap.bundle.min.js"></script>
  </body>
</html>
```
## Accordions & Collapse.
```HTML
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="./assets/css/bootstrap.min.css" />
    <title>Bootstrap Sandbox | Accordion & Collapse</title>
  </head>
  <body>
    <div class="container">
      <h1 class="mb-5">Accordion & Collapse</h1>

      <!-- Accordion -->
      <div id="myaccordion" class="accordion">
        <div class="accordion-item">
          <h2 class="accordion-header">
            <button
              class="accordion-button"
              data-bs-toggle="collapse"
              data-bs-target="#collapseOne"
            >
              Accordion 1
            </button>
          </h2>
          <div
            id="collapseOne"
            class="accordion-collapse collapse show"
            data-bs-parent="#myaccordion"
          >
            <div class="accordion-body">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Quae,
              culpa repellendus molestias quia consequatur vel delectus sed
              fugiat exercitationem perspiciatis praesentium quidem asperiores
              iusto placeat saepe voluptate neque doloribus tenetur.
            </div>
          </div>
        </div>

        <div class="accordion-item">
          <h2 class="accordion-header">
            <button
              class="accordion-button"
              data-bs-toggle="collapse"
              data-bs-target="#collapseTwo"
            >
              Accordion 2
            </button>
          </h2>
          <div
            id="collapseTwo"
            class="accordion-collapse collapse"
            data-bs-parent="#myaccordion"
          >
            <div class="accordion-body">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Quae,
              culpa repellendus molestias quia consequatur vel delectus sed
              fugiat exercitationem perspiciatis praesentium quidem asperiores
              iusto placeat saepe voluptate neque doloribus tenetur.
            </div>
          </div>
        </div>

        <div class="accordion-item">
          <h2 class="accordion-header">
            <button
              class="accordion-button"
              data-bs-toggle="collapse"
              data-bs-target="#collapseThree"
            >
              Accordion 3
            </button>
          </h2>
          <div
            id="collapseThree"
            class="accordion-collapse collapse show"
            data-bs-parent="#myaccordion"
          >
            <div class="accordion-body">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Quae,
              culpa repellendus molestias quia consequatur vel delectus sed
              fugiat exercitationem perspiciatis praesentium quidem asperiores
              iusto placeat saepe voluptate neque doloribus tenetur.
            </div>
          </div>
        </div>
      </div>

      <br /><br />

      <!-- Collapse -->
      <div class="my-3">
        <button
          class="btn btn-primary"
          data-bs-toggle="collapse"
          data-bs-target="#mycontent"
        >
          Toggle Content
        </button>
      </div>

      <div class="collapse" id="mycontent">
        <div class="card">
          <div class="card-body">
            Lorem ipsum dolor sit amet consectetur, adipisicing elit. Cumque
            harum facilis voluptas reprehenderit dolorum! Quia, molestiae!
            Ducimus quidem eaque nam ullam minima dolorem, blanditiis aliquam
            cum nemo quos debitis nisi.
          </div>
        </div>
      </div>

      <!-- Don't go past here -->
    </div>
    <div style="margin-top: 350px"></div>

    <script src="./assets/js/bootstrap.bundle.min.js"></script>
  </body>
</html>
```
## Carousel.
```HTML
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="./assets/css/bootstrap.min.css" />
    <title>Bootstrap Sandbox | Carousel</title>
  </head>
  <body>
    <div class="container">
      <h1 class="mb-5">Carousel</h1>

      <!-- Carousel -->
      <div class="carousel slide" id="slider">
        <!-- Indicators -->
        <div class="carousel-indicators">
          <button
            class="active"
            data-bs-slide-to="0"
            data-bs-target="#slider"
          ></button>
          <button data-bs-slide-to="1" data-bs-target="#slider"></button>
          <button data-bs-slide-to="2" data-bs-target="#slider"></button>
        </div>

        <div class="carousel-inner">
          <div class="carousel-item active">
            <img
              src="https://kajabi-storefronts-production.kajabi-cdn.com/kajabi-storefronts-production/file-uploads/themes/2152537062/settings_images/18b2741-a50-55da-37bc-c77252583e_modernjs.webp"
              alt=""
              class="d-block w-100"
            />
            <div
              class="carousel-caption d-none d-md-block bg-secondary opacity-75"
            >
              <h5>Modern JS From The Beginning</h5>
              <p>Lorem ipsum dolor sit amet.</p>
            </div>
          </div>

          <div class="carousel-item">
            <img
              src="https://kajabi-storefronts-production.kajabi-cdn.com/kajabi-storefronts-production/file-uploads/themes/2152537062/settings_images/a6146c8-c550-e60d-83d-da0202f6bd7_258ea558-245b-4906-b8d6-3412e8d6f0a7.jpg"
              alt=""
              class="d-block w-100"
            />
            <div
              class="carousel-caption d-none d-md-block bg-secondary opacity-75"
            >
              <h5>MERN Stack From Scratch</h5>
              <p>Lorem ipsum dolor sit amet.</p>
            </div>
          </div>

          <div class="carousel-item">
            <img
              src="https://kajabi-storefronts-production.kajabi-cdn.com/kajabi-storefronts-production/file-uploads/themes/2152537062/settings_images/825ccb4-0ffc-3c0f-8f8e-4f043c0027_2ce67a0-d43b-28cb-bc33-e0acb621bde_Tailwind_CSS_Course.webp"
              alt=""
              class="d-block w-100"
            />
            <div
              class="carousel-caption d-none d-md-block bg-secondary opacity-75"
            >
              <h5>Tailwind From Scratch</h5>
              <p>Lorem ipsum dolor sit amet.</p>
            </div>
          </div>
        </div>
        <!-- Buttons -->
        <button
          class="carousel-control-prev"
          data-bs-slide="prev"
          data-bs-target="#slider"
        >
          <span class="carousel-control-prev-icon"></span>
          <span class="visually-hidden">Previous</span>
        </button>
        <button
          class="carousel-control-next"
          data-bs-slide="next"
          data-bs-target="#slider"
        >
          <span class="carousel-control-next-icon"></span>
          <span class="visually-hidden">Next</span>
        </button>
      </div>

      <!-- Don't go past here -->
    </div>
    <div style="margin-top: 350px"></div>

    <script src="./assets/js/bootstrap.bundle.min.js"></script>
  </body>
</html>
```
## Toast Notification.
```HTML
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="./assets/css/bootstrap.min.css" />

    <title>Bootstrap Sandbox | Toasts</title>
  </head>
  <body>
    <div class="container">
      <h1 class="mb-5">Toasts</h1>

      <button id="toastBtn" class="btn btn-primary">Show Toast</button>

      <div class="toast-container position-fixed bottom-0 end-0 p-3">
        <div class="toast" id="myToast">
          <div class="toast-header text-bg-danger">
            <div class="me-auto">Bootstrap</div>
            <small>11 mins ago</small>
          </div>
          <div class="toast-body text-bg-danger">
            Hello World! This is a toast message!
          </div>
        </div>
      </div>

      <!-- Don't go past here -->
    </div>
    <div style="margin-top: 350px"></div>

    <script src="./assets/js/bootstrap.bundle.min.js"></script>

    <script>
      const toastTrigger = document.querySelector('#toastBtn');
      const toast = document.querySelector('#myToast');

      if (toastTrigger) {
        const toastBootstrap = bootstrap.Toast.getOrCreateInstance(toast);

        toastTrigger.addEventListener('click', () => {
          toastBootstrap.show();
        });
      }
    </script>
  </body>
</html>

```
## Spinners.
```HTML
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="./assets/css/bootstrap.min.css" />
    <title>Bootstrap Sandbox | Spinners</title>
  </head>
  <body>
    <div class="container">
      <h1 class="mb-5">Spinners</h1>

      <!-- Border Spinner -->
      <div class="spinner-border" role="status">
        <span class="visually-hidden"></span>
      </div>

      <br /><br />

      <!-- Colors -->
      <div class="spinner-border text-primary" role="status">
        <span class="visually-hidden"></span>
      </div>
      <div class="spinner-border text-secondary" role="status">
        <span class="visually-hidden">Loading...</span>
      </div>
      <div class="spinner-border text-success" role="status">
        <span class="visually-hidden">Loading...</span>
      </div>
      <div class="spinner-border text-danger" role="status">
        <span class="visually-hidden">Loading...</span>
      </div>
      <div class="spinner-border text-warning" role="status">
        <span class="visually-hidden">Loading...</span>
      </div>
      <div class="spinner-border text-info" role="status">
        <span class="visually-hidden">Loading...</span>
      </div>
      <div class="spinner-border text-light" role="status">
        <span class="visually-hidden">Loading...</span>
      </div>
      <div class="spinner-border text-dark" role="status">
        <span class="visually-hidden">Loading...</span>
      </div>

      <br /><br />

      <!-- Growing Spinner -->
      <div class="spinner-grow" role="status">
        <span class="visually-hidden"></span>
      </div>

      <br /><br />

      <!-- Align Center -->
      <div class="d-flex justify-content-center">
        <div class="spinner-border" role="status">
          <span class="visually-hidden"></span>
        </div>
      </div>

      <br /><br />

      <!-- Size -->
      <div class="spinner-border spinner-border-sm" role="status">
        <span class="visually-hidden"></span>
      </div>

      <div
        class="spinner-border"
        role="status"
        style="height: 5rem; width: 5rem"
      >
        <span class="visually-hidden"></span>
      </div>

      <br /><br />

      <!-- In Buttons -->
      <button class="btn btn-primary">
        <span class="spinner-border spinner-border-sm"></span> Loading...
      </button>

      <!-- Don't go past here -->
    </div>
    <div style="margin-top: 350px"></div>

    <script src="./assets/js/bootstrap.bundle.min.js"></script>
  </body>
</html>

```
## Modals.
```HTML
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="./assets/css/bootstrap.min.css" />

    <title>Bootstrap Sandbox | Modal</title>
  </head>
  <body>
    <div class="container">
      <h1 class="mb-5">Modal</h1>

      <!-- Modal Button -->
      <button
        type="button"
        class="btn btn-primary"
        data-bs-toggle="modal"
        data-bs-target="#myModal"
      >
        Open Modal
      </button>

      <!-- Modal -->
      <div class="modal fade" id="myModal">
        <div class="modal-dialog">
          <div class="modal-content">
            <div class="modal-header">
              <h1 class="modal-title fs-5" id="myModalLabel">Modal Title</h1>
              <button class="btn-close" data-bs-dismiss="modal"></button>
            </div>
            <div class="modal-body">
              Lorem ipsum dolor sit amet consectetur, adipisicing elit.
              Blanditiis, debitis laboriosam. Quidem cumque incidunt sapiente,
              ea voluptates provident illo enim aspernatur necessitatibus
              deserunt odio ab! Inventore cum eum nesciunt maiores.
            </div>
            <div class="modal-footer">
              <button class="btn btn-secondary" data-bs-dismiss="modal">
                Close
              </button>
              <button class="btn btn-primary">Save Changes</button>
            </div>
          </div>
        </div>
      </div>

      <!-- Don't go past here -->
    </div>
    <div style="margin-top: 350px"></div>

    <script src="./assets/js/bootstrap.bundle.min.js"></script>
  </body>
</html>
```
## Popovers & Tooltips.
```HTML
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="./assets/css/bootstrap.min.css" />
    <title>Bootstrap Sandbox | Popovers & Tooltips</title>
  </head>
  <body>
    <div class="container">
      <h1 class="mb-5">Popovers & Tooltips</h1>

      <!-- Popover -->
      <button
        class="btn btn-danger btn-lg"
        id="popover"
        data-bs-toggle="popover"
        data-bs-title="Popover Title"
        data-bs-content="This is the popover content"
      >
        Toggle Popover
      </button>

      <br /><br />

      <!-- Tooltip -->
      <p>
        Lorem ipsum dolor, sit amet consectetur adipisicing elit. Veniam culpa
        <a href="#" data-bs-toggle="tooltip" data-bs-title="Tooltip One"
          >tooltip one</a
        >reiciendis pariatur modi, veritatis eius consequatur repellat soluta
        quas consequuntur dolore tempora id!
        <a href="#" data-bs-toggle="tooltip" data-bs-title="Tooltip Two"
          >tooltip two</a
        >Perspiciatis obcaecati, laudantium a consequuntur sunt placeat!
      </p>

      <!-- Don't go past here -->
    </div>
    <div style="margin-top: 350px"></div>

    <script src="./assets/js/bootstrap.bundle.min.js"></script>
    <script>
      const popoverEl = document.getElementById('popover');
      const popover = new bootstrap.Popover(popoverEl);

      const tooltipTriggerList = document.querySelectorAll(
        '[data-bs-toggle="tooltip"]'
      );

      const tooltipList = [...tooltipTriggerList].map(
        (tooltipTriggerEl) => new bootstrap.Tooltip(tooltipTriggerEl)
      );
    </script>
  </body>
</html>
```
## Darkmode Toggle.
```HTML
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="./assets/css/bootstrap.min.css" />

    <title>Bootstrap Sandbox | Toggle Dark Mode</title>
  </head>
  <body>
    <div class="container">
      <h1 class="mb-5">Toggle Dark Mode</h1>

      <div class="card mb-4" style="width: 18rem">
        <div class="card-header">This is a card</div>
        <div class="card-body">
          Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ea ducimus,
          facere necessitatibus dolorem veniam officiis voluptatibus blanditiis
          quos eius ipsam.
        </div>
      </div>

      <button class="btn btn-dark" data-bs-theme-value="dark">
        Enable Dark Mode
      </button>

      <button class="btn btn-light" data-bs-theme-value="light">
        Enable Light Mode
      </button>

      <!-- Don't go past here -->
    </div>
    <div style="margin-top: 350px"></div>

    <script src="./assets/js/bootstrap.bundle.min.js"></script>
    <script src="./assets/js/darkmodetoggle.js"></script>
    <script></script>
  </body>
</html>
```
## Template
```HTML
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="./assets/css/bootstrap.min.css" />
    <title>Bootstrap Sandbox</title>
  </head>
  <body>
    <div class="container">
      <h1 class="mb-5">Topic</h1>

      <!-- Don't go past here -->
    </div>
    <div style="margin-top: 350px"></div>

    <script src="./assets/js/bootstrap.bundle.min.js"></script>
  </body>
</html>
```

## Sample
```HTML

```
<table>
    <thead>
    </thead>
    <tbody>
      <tr>
        <td></br> 
        </td>
        <td>
          <ul>
            <li></li>
            <li></li>
            <li></li>
            <li></li>
          </ul>
      </td>
      </tr>
    </tbody>
</table> 


# Pomodoros.
<table>
    <thead>
    </thead>
    <tbody>
    <tr>
        <td>Pomodoro</br> 
        </td>
        <td>
          <ul>
            <li>1 - 2//2024</li>
            <li>2 - 2//2024</li>
            <li>3 - 2//2024</li>
            <li>4 - 2//2024</li>
          </ul>
      </td>
      </tr>
      <tr>
        <td>Pomodoro</br> 
        </td>
        <td>
          <ul>
            <li>1 - 2/15/2024</li>
            <li>2 - 2/15/2024</li>
            <li>3 - 2/15/2024</li>
            <li>4 - 2/15/2024</li>
          </ul>
      </td>
      </tr>
      <tr>
        <td>Pomodoro</br> 
        </td>
        <td>
          <ul>
            <li>1 - 2/10/2024</li>
            <li>2 - 2/10/2024</li>
            <li>3 - 2/11/2024</li>
            <li>4 - 2/11/2024</li>
          </ul>
      </td>
      </tr>
      <tr>
        <td>Pomodoro</br> 
        </td>
        <td>
          <ul>
            <li>1 - 2/9/2024</li>
            <li>2 - 2/9/2024</li>
            <li>3 - 2/9/2024</li>
            <li>4 - 2/9/2024</li>
          </ul>
      </td>
      </tr>
      <tr>
        <td>Pomodoro</br> 
        </td>
        <td>
          <ul>
            <li>1 - 2//2024</li>
            <li>2 - 2//2024</li>
            <li>3 - 2//2024</li>
            <li>4 - 2//2024</li>
          </ul>
      </td>
      </tr>
    </tbody>
</table> 