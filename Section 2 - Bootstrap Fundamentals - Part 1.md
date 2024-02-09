# Section 2: Bootstrap Fundamentals - Part 1
## Containers
![Bootstrap Breakpoint Container Chart](./images/5-bootstrap-breakpoints.png)
```HTML
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="./assets/css/bootstrap.min.css" />

    <title>Bootstrap Sandbox | Containers</title>
  </head>
  <body>
    <h1 class="mb-5">Containers</h1>

    <div class="container"><!-- Add container class -->
      <h3>Container</h3>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aliquid
        similique porro praesentium quo. Aperiam officiis eos atque iure quo
        nostrum voluptate laudantium distinctio! Hic pariatur in exercitationem
        eaque ducimus aperiam.
      </p>
    </div>

    <div class="container-sm"><!-- container small -->
      <h3>Container Small</h3>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aliquid
        similique porro praesentium quo. Aperiam officiis eos atque iure quo
        nostrum voluptate laudantium distinctio! Hic pariatur in exercitationem
        eaque ducimus aperiam.
      </p>
    </div>

    <div class="container-md"><!-- container medium-->
      <h3>Container Medium</h3>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aliquid
        similique porro praesentium quo. Aperiam officiis eos atque iure quo
        nostrum voluptate laudantium distinctio! Hic pariatur in exercitationem
        eaque ducimus aperiam.
      </p>
    </div>

    <div class="container-lg"><!-- container large-->
      <h3>Container Large</h3>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aliquid
        similique porro praesentium quo. Aperiam officiis eos atque iure quo
        nostrum voluptate laudantium distinctio! Hic pariatur in exercitationem
        eaque ducimus aperiam.
      </p>
    </div>

    <div class="container-xl"><!-- container extra large -->
      <h3>Container Extra Large</h3>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aliquid
        similique porro praesentium quo. Aperiam officiis eos atque iure quo
        nostrum voluptate laudantium distinctio! Hic pariatur in exercitationem
        eaque ducimus aperiam.
      </p>
    </div>

    <div class="container-xxl"><!-- container extra extra large -->
      <h3>Container Extra Extra Large</h3>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aliquid
        similique porro praesentium quo. Aperiam officiis eos atque iure quo
        nostrum voluptate laudantium distinctio! Hic pariatur in exercitationem
        eaque ducimus aperiam.
      </p>
    </div>

    <div class="container-fluid"><!-- container fluid -->
      <h3>Container Fluid</h3>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aliquid
        similique porro praesentium quo. Aperiam officiis eos atque iure quo
        nostrum voluptate laudantium distinctio! Hic pariatur in exercitationem
        eaque ducimus aperiam.
      </p>
    </div>

    <script src="./assets/js/bootstrap.bundle.min.js"></script>
  </body>
</html> 
```
## Typography.
```HTML
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="./assets/css/bootstrap.min.css" />
    <title>Bootstrap Sandbox | Typography</title>
  </head>
  <body>
    <div class="container">
      <h1 class="mb-5">Typography</h1>

      <!-- Headings -->
      <h1>Heading 1</h1>
      <h2>Heading 2</h2>
      <h3>Heading 3</h3>
      <h4>Heading 4</h4>
      <h5>Heading 5</h5>
      <h6>Heading 6</h6>

      <br /><br />

      <!-- Heading Classes -->
      <p class="h1">Heading 1 Paragraph</p><!-- Heading 1 -->
      <p class="h2">Heading 2 Paragraph</p><!-- Heading 2 -->
      <p class="h3">Heading 3 Paragraph</p><!-- Heading 3 -->
      <p class="h4">Heading 4 Paragraph</p><!-- Heading 4 -->
      <p class="h5">Heading 5 Paragraph</p><!-- Heading 5 -->
      <p class="h6">Heading 6 Paragraph</p><!-- Heading 6 -->

      <br /><br />

      <!-- Display Headings -->
      <h1 class="display-1">Display 1</h1><!-- class="display-1" -->
      <h1 class="display-2">Display 2</h1><!-- class="display-2" -->
      <h1 class="display-3">Display 3</h1><!-- class="display-3" -->
      <h1 class="display-4">Display 4</h1><!-- class="display-4" -->
      <h1 class="display-5">Display 5</h1><!-- class="display-5" -->
      <h1 class="display-6">Display 6</h1><!-- class="display-6" -->

      <br /><br />

      <!-- Inline Classes -->
      <p class="lead"><!-- class="lead" -->
        Lorem, ipsum dolor sit
        <span class="">This is highlighted text</span>amet consectetur
        adipisicing <span class="">This is strong text</span>Lorem ipsum dolor
        sit. <span class="">This is strikethrough text</span> Lorem ipsum dolor
        sit amet. <span class="">This is underlined tect</span> Lorem ipsum
        dolor sit amet. <span class="">This is italic text</span>
      </p>

      <br /><br />

      <!-- Blockquote -->
      <blockquote class="blockquote"><!-- class="blockquote"-->
        <p>This is a blockquote</p>
      </blockquote>

      <br /><br />

      <!-- Font Weight -->
      <p class="fw-bold">This is bold text</p><!-- fw-bold -->
      <p class="fw-bolder">This is bolder text (relative to the parent element).</p><!-- fw-bolder-->
      <p class="fw-semibold">This is semibold text</p><!-- fw-semibold -->
      <p class="fw-medium">This is a medium weight</p><!-- fw-medium -->
      <p class="fw-normal">This is a normal weight</p><!-- fw-normal -->
      <p class="fw-light">This is light weight text</p><!-- fw-light -->
      <p class="fw-lighter"> <!-- fw-lighter -->
        This is lighter weight text (relative to the parent element).
      </p>
      <p class="fst-italic">This is italic text.</p><!-- fst-italic -->
      <p class="fst-normal">This is text with normal font style</p><!-- fst-normal -->

      <br /><br />

      <!-- Line Height -->
      <p class="lh-1"><!-- lh-1 -->
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Itaque dolor
        sit obcaecati architecto necessitatibus velit? Excepturi culpa ipsa enim
        eveniet, alias assumenda quas omnis laborum atque ipsam ipsum minima a.
      </p>
      <p class="lh-sm"><!-- lh-sm -->
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Itaque dolor
        sit obcaecati architecto necessitatibus velit? Excepturi culpa ipsa enim
        eveniet, alias assumenda quas omnis laborum atque ipsam ipsum minima a.
      </p>
      <p class="lh-base"><!-- lh-base -->
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Itaque dolor
        sit obcaecati architecto necessitatibus velit? Excepturi culpa ipsa enim
        eveniet, alias assumenda quas omnis laborum atque ipsam ipsum minima a.
      </p>
      <p class="lh-lg"><!-- lh-lg -->
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Itaque dolor
        sit obcaecati architecto necessitatibus velit? Excepturi culpa ipsa enim
        eveniet, alias assumenda quas omnis laborum atque ipsam ipsum minima a.
      </p>

      <br /><br />

      <!-- Text Transform -->
      <p class="text-lowercase">lowercased text</p><!-- text-lowercase -->
      <p class="text-uppercase">uppercased text</p><!-- text-uppercase -->
      <p class="text-capitalized">capitialized text</p><!-- text-capitalized -->

      <br /><br />

      <!-- Text Alignment -->
      <p class="text-start">Start aligned text on all viewport sizes.</p><!-- text-start -->
      <p class="text-center">Center aligned text on all viewport sizes.</p><!-- text-center -->
      <p class="text-end">End aligned text on all viewport sizes.</p><!-- text-end -->

      <p class="text-sm-end">Start aligned text on viewports sized SM (small) or wider.</p><!-- text-sm-end -->
      <p class="text-md-end">
        Start aligned text on viewports sized MD (medium) or wider.
      </p><!-- text-md-end -->
      <p class="text-lg-end">Start aligned text on viewports sized LG (large) or wider.</p><!-- text-lg-end -->
      <p class="text-xl-end">
        Start aligned text on viewports sized XL (extra-large) or wider.
      </p><!-- text-xl-end -->

      <!-- Don't go past here -->
    </div>
    <div style="margin-top: 350px"></div>

    <script src="./assets/js/bootstrap.bundle.min.js"></script>
  </body>
</html>
```
## Display & Position.
```HTML
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="./assets/css/bootstrap.min.css" />
    <title>Bootstrap Sandbox | Display & Position</title>
  </head>
  <body>
    <div class="container">
      <h1 class="mb-5">Display & Position</h1>

      <!-- Display None -->
      <p class="d-none">This text is hidden</p><!-- d-none -->

      <br /><br />

      <!-- Display Inline -->
      <div class="d-inline">This text is inline</div><!-- d-inline -->
      <div class="d-inline">This text is inline</div><!-- d-inline -->

      <br /><br />

      <!-- Display Block -->
      <span class="d-block">This span is block</span><!-- d-block -->
      <span class="d-block">This span is block</span><!-- d-block -->

      <br /><br />

      <!-- Display Inline Block -->
      <span class="d-inline-block" style="width: 500px">This span is inline-block</span><!-- d-inline-block -->
      <span class="d-inline-block">This span is inline-block</span><!-- d-inline-block -->

      <br /><br />

      <!-- Hide on small screens -->
      <div class="d-none d-md-block">This div is hidden on mobile</div><!-- d-none d-md-block -->

      <br /><br />

      <!-- Hide on medium screens and up -->
      <div class="d-block d-md-none">This div is hidden on medium screens and up</div> <!-- d-block d-md-none -->

      <br /><br />

      <!-- POSITIONING -->

      <!-- Position Static -->
      <p class="position-static">This text is static</p><!-- position-static -->

      <br /><br />
      
      <div class="position-relative" style="height: 200px; width: 200px; background: #ccc">

        <p class="position-absolute start-0 bottom-0" style="top:40px"></p><!-- position-absolute start-0 bottom-0  style="top:40px"-->
      
      </div><!-- position-relative -->

      <br /><br />

      <!-- Position Fixed -->
      <p class="position-fixed">This text is fixed</p><!-- position-fixed -->

      <br /><br />

      <p class="fixed-top">This text is fixed top</p><!-- fixed-top -->
      <p class="fixed-bottom">This text is fixed bottom</p><!-- fixed-bottom -->

      <br /><br />

      <!-- Sticky Top -->
      <p class="">This text is sticky top</p><!--  -->

      <br /><br />

      <!-- Filler Text -->
      <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Itaque
        perferendis voluptatibus eveniet nesciunt explicabo architecto
        voluptatem! Laudantium mollitia voluptate sit dolor! Maiores architecto
        iure placeat, deleniti iste doloribus velit quam magnam ex blanditiis
        itaque ipsum consectetur dolorem debitis optio temporibus facere error
        eaque nesciunt accusantium possimus. Dolorum assumenda molestias
        cupiditate exercitationem esse, nam inventore nesciunt eaque, ex
        reiciendis distinctio sequi optio sint at a nulla. Iure rem architecto
        voluptatem aliquam molestiae odit exercitationem vitae, debitis neque
        nostrum aperiam fugiat tempore magnam cum! Harum excepturi iusto iste
        porro ex cum optio magnam labore doloremque culpa possimus asperiores
        aliquid incidunt, hic, necessitatibus neque obcaecati aliquam. Aperiam,
        excepturi facere dolores temporibus corporis dicta atque iusto
        repudiandae debitis voluptas quasi magni quisquam sit veniam
        necessitatibus veritatis fugit dolorum rerum animi? Beatae facere ipsam
        distinctio. Minima unde tempore maiores aliquid sunt nihil dolorum,
        itaque alias, possimus sequi nobis! Commodi maxime, quos reprehenderit
        mollitia veritatis ipsa nobis quo numquam quis rem expedita temporibus
        laudantium nulla, exercitationem magnam, voluptates et? Voluptates,
        cumque laboriosam soluta saepe explicabo quisquam ex a voluptatum
        assumenda quia vel iusto reiciendis eaque provident! Eveniet numquam
        aut, rerum et perferendis praesentium, maiores eaque nihil earum
        voluptate dolores dolore blanditiis pariatur aliquid aspernatur
        consectetur! Minus, voluptatum autem veniam ducimus id earum similique
        alias cum impedit blanditiis, suscipit, tempora iusto nemo ea. Eum
        ducimus architecto dolorum fugit saepe nesciunt, fuga aspernatur ratione
        debitis quos sequi, nisi eius inventore enim magni id et perspiciatis
        reprehenderit, animi adipisci voluptates porro. Enim, error non! Aliquam
        sapiente maxime praesentium ullam possimus recusandae illum qui non amet
        dolorum earum error, provident, voluptas quas eveniet minus voluptatibus
        excepturi eaque laboriosam. Maxime, fugiat. Sed ipsum aliquam suscipit
        officiis excepturi omnis, optio possimus placeat laudantium quam facilis
        dolore voluptate aperiam expedita pariatur ipsa recusandae perferendis
        perspiciatis nesciunt quos earum praesentium dolores! Error expedita
        nulla inventore atque voluptates excepturi ea fuga optio blanditiis
        totam nesciunt saepe, voluptate minima voluptatem accusamus vero
        aliquid! Necessitatibus ut corporis illo praesentium, assumenda,
        perspiciatis quo magni similique, animi cupiditate iure. Corrupti
        reiciendis harum nobis, aperiam itaque dolores accusantium voluptates
        quos mollitia amet dignissimos inventore tempora laudantium, fuga
        repudiandae voluptate odit tenetur? Doloremque soluta rem a
        consequuntur, consectetur obcaecati. Quia hic architecto officiis
        sapiente dolore odit, illum corporis laboriosam. Quas quidem doloribus
        quaerat rerum est, ad repudiandae provident culpa reiciendis illum
        soluta nesciunt non iusto beatae earum accusamus maiores recusandae
        ducimus sint, minus consectetur? Natus beatae officiis molestiae
        explicabo excepturi, sapiente vitae provident aut consequatur ea atque
        velit laborum. Nulla amet sequi quisquam fugiat repellendus libero
        dolor. Quisquam voluptates quos sapiente est doloribus fugit, quam
        necessitatibus commodi? Ex, consectetur. Incidunt, explicabo quaerat
        iusto aliquid corporis cumque iure perferendis ipsam at velit vero nulla
        quisquam ab dicta odio illo! Numquam cupiditate consequatur ut,
        voluptatum quas excepturi quis nulla error maiores cum illo nesciunt
        voluptatem accusantium itaque iusto dolor modi! Mollitia eos culpa
        nostrum ducimus rem quasi animi tenetur reprehenderit velit nesciunt
        placeat, reiciendis eligendi saepe officiis nihil rerum odio ratione
        illo voluptatibus ipsa consequuntur dicta voluptatum impedit? Aperiam
        veritatis fugit totam. Labore.
      </p><!--  -->
      <!-- Don't go past here -->
    </div>
    <div style="margin-top: 350px"></div>

    <script src="./assets/js/bootstrap.bundle.min.js"></script>
  </body>
</html>
```
## Background & Text Colors.
```HTML
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="./assets/css/bootstrap.min.css" />
    <title>Bootstrap Sandbox | Background & Text Colors</title>
  </head>
  <body>
    <div class="container">
      <h1 class="mb-5">Background & Text Colors</h1>

      <!-- Background Colors -->
      <div class="bg-primary">.bg-primary</div><!-- bg-primary -->
      <div class="bg-secondary">.bg-secondary</div><!-- bg-secondary -->
      <div class="bg-success">.bg-success</div><!-- bg-success -->
      <div class="bg-danger">.bg-danger</div><!-- bg-danger -->
      <div class="bg-warning">.bg-warning</div><!-- bg-warning -->
      <div class="bg-info">.bg-info</div><!-- bg-info -->
      <div class="bg-light">.bg-light</div><!-- bg-light -->
      <div class="bg-dark">.bg-dark</div><!-- bg-dark -->
      <div class="bg-black">.bg-black</div><!-- bg-black -->
      <div class="bg-white">.bg-white</div><!-- bg-white -->
      <div class="bg-transparent">.bg-transparent</div><!-- bg-transparent -->

      <br /><br />

      <!-- Text Background Colors -->
      <div class="text-bg-primary">.bg-primary</div><!-- text-bg-primary -->
      <div class="text-bg-secondary">.bg-secondary</div><!-- text-bg-secondary -->
      <div class="text-bg-success">.bg-success</div><!-- text-bg-success -->
      <div class="text-bg-danger">.bg-danger</div><!-- text-bg-danger -->
      <div class="text-bg-warning">.bg-warning</div><!-- text-bg-warning -->
      <div class="text-bg-info">.bg-info</div><!-- text-bg-info -->
      <div class="text-bg-light">.bg-light</div><!-- text-bg-light -->
      <div class="text-bg-dark">.bg-dark</div><!-- text-bg-dark -->
      <div class="text-bg-black">.bg-black</div><!-- text-bg-black -->
      <div class="text-bg-white">.bg-white</div><!-- text-bg-white -->
      <div class="text-bg-transparent">.bg-transparent</div><!-- text-bg-transparent -->

      <br /><br />

      <!-- Text Colors -->
      <div class="text-primary">.bg-primary</div><!-- text-primary -->
      <div class="text-secondary">.bg-secondary</div><!-- text-secondary -->
      <div class="text-success">.bg-success</div><!-- text-success -->
      <div class="text-danger">.bg-danger</div><!-- text-danger -->
      <div class="text-warning">.bg-warning</div><!-- text-warning -->
      <div class="text-info">.bg-info</div><!-- text-info -->
      <div class="text-light">.bg-light</div><!-- text-light -->
      <div class="text-dark">.bg-dark</div><!-- text-dark -->
      <div class="text-black">.bg-black</div><!-- text-black -->
      <div class="text-white">.bg-white</div><!-- text-white -->
      <div class="text-transparent">.bg-transparent</div><!-- text-transparent -->

      <br /><br />

      <!-- Gradients -->
      <div class="text-bg-primary bg-gradient">.bg-primary</div><!-- text-bg-primary bg-gradient -->
      <div class="text-bg-secondary bg-gradient">.bg-secondary</div><!-- text-bg-secondary bg-gradient -->
      <div class="text-bg-success bg-gradient">.bg-success</div><!-- text-bg-success bg-gradient -->
      <div class="text-bg-danger bg-gradient">.bg-danger</div><!-- text-bg-danger bg-gradient -->
      <div class="text-bg-warning bg-gradient">.bg-warning</div><!-- text-bg-warning bg-gradient -->
      <div class="text-bg-info bg-gradient">.bg-info</div><!-- text-bg-info bg-gradient -->
      <div class="text-bg-light bg-gradient">.bg-light</div><!-- text-bg-light bg-gradient -->
      <div class="text-bg-dark bg-gradient">.bg-dark</div><!-- text-bg-dark bg-gradient -->
      <div class="text-bg-black bg-gradient">.bg-black</div><!-- text-bg-black bg-gradient -->
      <div class="text-bg-white bg-gradient">.bg-white</div><!-- text-bg-white bg-gradient -->
      <div class="text-bg-transparent bg-gradient">.bg-transparent</div><!-- text-bg-transparent bg-gradient -->


      <br /><br />

      <!-- Background Opacity -->
      <div class="text-bg-success">Default success background</div><!-- text-bg-success bg-opacity-75 -->
      <div class="text-bg-success bg-opacity-75">75% opacity success background</div><!-- text-bg-success bg-opacity-75 -->
      <div class="text-bg-success bg-opacity-50">50% opacity success background</div><!-- text-bg-success bg-opacity-50 -->
      <div class="text-bg-success bg-opacity-25">25% opacity success background</div><!-- text-bg-success bg-opacity-10 -->
      <div class="text-bg-success bg-opacity-10">10% opacity success background</div><!-- text-bg-success bg-opacity-10 -->

      <br /><br />

      <!-- Text Opacity -->
      <div class="text-primary">Default primary text</div><!--  -->
      <div class="text-primary text-opacity-75">75% opacity primary text</div><!--  text-primary text-opacity-75 -->
      <div class="text-primary text-opacity-50">50% opacity primary text</div><!--  text-primary text-opacity-50 -->
      <div class="text-primary text-opacity-25">25% opacity primary text</div><!--  text-primary text-opacity-25 -->

      <!-- Link Colors -->
      <p><a href="#" class="link-primary">Primary link</a></p><!-- link-primary -->
      <p><a href="#" class="link-secondary">Secondary link</a></p><!-- link-secondary -->
      <p><a href="#" class="link-success">Success link</a></p><!-- link-success -->
      <p><a href="#" class="link-danger">Danger link</a></p><!-- link-danger -->
      <p><a href="#" class="link-warning">Warning link</a></p><!-- link-warning -->
      <p><a href="#" class="link-info">Info link</a></p><!-- link-info -->

      <!-- Don't go past here -->
    </div>
    <div style="margin-top: 350px"></div>

    <script src="./assets/js/bootstrap.bundle.min.js"></script>
  </body>
</html>
```
## Spacing
![Spacing Values](./images/6-spacing-values.png)
```HTML
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="./assets/css/bootstrap.min.css" />
    <title>Bootstrap Sandbox | Spacing</title>
  </head>
  <body>
    <div class="container">
      <h1 class="mb-5">Spacing</h1>
      <!-- Margin All -->
      <div class="text-bg-dark m-1">Lorem, ipsum dolor.</div><!-- text-bg-dark m-1 -->
      <div class="text-bg-dark m-2">Lorem, ipsum dolor.</div><!-- text-bg-dark m-2 -->
      <div class="text-bg-dark m-3">Lorem, ipsum dolor.</div><!-- text-bg-dark m-3 -->
      <div class="text-bg-dark m-4">Lorem, ipsum dolor.</div><!-- text-bg-dark m-4 -->
      <div class="text-bg-dark m-5">Lorem, ipsum dolor.</div><!-- text-bg-dark m-5 -->

      <!-- Margin Top & Bottom -->
      <div class="text-bg-success my-1 ">Lorem, ipsum dolor.</div><!-- text-bg-success  my-1 -->
      <div class="text-bg-success my-2 ">Lorem, ipsum dolor.</div><!-- text-bg-success  my-2 -->
      <div class="text-bg-success my-3 ">Lorem, ipsum dolor.</div><!-- text-bg-success  my-3 -->
      <div class="text-bg-success my-4 ">Lorem, ipsum dolor.</div><!-- text-bg-success  my-4 -->
      <div class="text-bg-success my-5 ">Lorem, ipsum dolor.</div><!-- text-bg-success  my-5 -->

      <!-- Margin Left & Right -->
      <div class="text-bg-secondary mx-1">Lorem, ipsum dolor.</div><!-- text-bg-secondary mx-1 -->
      <div class="text-bg-secondary mx-2">Lorem, ipsum dolor.</div><!-- text-bg-secondary mx-2 -->
      <div class="text-bg-secondary mx-3">Lorem, ipsum dolor.</div><!-- text-bg-secondary mx-3 -->
      <div class="text-bg-secondary mx-4">Lorem, ipsum dolor.</div><!-- text-bg-secondary mx-4 -->
      <div class="text-bg-secondary mx-5">Lorem, ipsum dolor.</div><!-- text-bg-secondary mx-5 -->

      <!-- Margin Top -->
      <div class="text-bg-danger mt-1">Lorem, ipsum dolor.</div><!-- text-bg-danger mt-1 -->
      <div class="text-bg-danger mt-2">Lorem, ipsum dolor.</div><!-- text-bg-danger mt-2 -->
      <div class="text-bg-danger mt-3">Lorem, ipsum dolor.</div><!-- text-bg-danger mt-3 -->
      <div class="text-bg-danger mt-4">Lorem, ipsum dolor.</div><!-- text-bg-danger mt-4 -->
      <div class="text-bg-danger mt-5">Lorem, ipsum dolor.</div><!-- text-bg-danger mt-5 -->

      <!-- Margin Bottom -->
      <div class="text-bg-warning mb-1">Lorem, ipsum dolor.</div><!-- text-bg-warning mb-1 -->
      <div class="text-bg-warning mb-2">Lorem, ipsum dolor.</div><!-- text-bg-warning mb-2 -->
      <div class="text-bg-warning mb-3">Lorem, ipsum dolor.</div><!-- text-bg-warning mb-3 -->
      <div class="text-bg-warning mb-4">Lorem, ipsum dolor.</div><!-- text-bg-warning mb-4 -->
      <div class="text-bg-warning mb-5">Lorem, ipsum dolor.</div><!-- text-bg-warning mb-5 -->

      <!-- Margin Left/Start -->
      <div class="text-bg-info ms-1">Lorem, ipsum dolor.</div><!-- text-bg-info ms-1 -->
      <div class="text-bg-info ms-2">Lorem, ipsum dolor.</div><!-- text-bg-info ms-2 -->
      <div class="text-bg-info ms-3">Lorem, ipsum dolor.</div><!-- text-bg-info ms-3 -->
      <div class="text-bg-info ms-4">Lorem, ipsum dolor.</div><!-- text-bg-info ms-4 -->
      <div class="text-bg-info ms-5">Lorem, ipsum dolor.</div><!-- text-bg-info ms-5 -->

      <!-- Margin Right/End -->
      <div class="text-bg-dark me-1">Lorem, ipsum dolor.</div><!--  text-bg-dark me-1 -->
      <div class="text-bg-dark me-2">Lorem, ipsum dolor.</div><!--  text-bg-dark me-2 -->
      <div class="text-bg-dark me-3">Lorem, ipsum dolor.</div><!--  text-bg-dark me-3 -->
      <div class="text-bg-dark me-4">Lorem, ipsum dolor.</div><!--  text-bg-dark me-4 -->
      <div class="text-bg-dark me-5">Lorem, ipsum dolor.</div><!--  text-bg-dark me-5 -->

      <!-- Margin Auto -->
      <div class="text-bg-warning w-50 m-auto">Lorem, ipsum dolor.</div><!-- text-bg-warning w-50 m-auto -->
      <div class="text-bg-warning w-50 my-auto">Lorem, ipsum dolor.</div><!-- text-bg-warning w-50 my-auto -->
      <div class="text-bg-warning w-50 mx-auto">Lorem, ipsum dolor.</div><!-- text-bg-warning w-50 mx-auto -->
      <div class="text-bg-warning w-50 ms-auto">Lorem, ipsum dolor.</div><!-- text-bg-warning w-50 ms-auto -->
      <div class="text-bg-warning w-50 me-auto">Lorem, ipsum dolor.</div><!-- text-bg-warning w-50 me-auto -->

      <!-- Padding All -->
      <div class="text-bg-dark my-1 p-1">Lorem, ipsum dolor.</div><!-- text-bg-dark my-1 p-1 -->
      <div class="text-bg-dark my-2 p-2">Lorem, ipsum dolor.</div><!-- text-bg-dark my-2 p-2 -->
      <div class="text-bg-dark my-3 p-3">Lorem, ipsum dolor.</div><!-- text-bg-dark my-3 p-3 -->
      <div class="text-bg-dark my-4 p-4">Lorem, ipsum dolor.</div><!-- text-bg-dark my-4 p-4 -->
      <div class="text-bg-dark my-5 p-5">Lorem, ipsum dolor.</div><!-- text-bg-dark my-5 p-5 -->

      <!-- Padding Top & Bottom -->
      <div class="text-bg-success py-1">Lorem, ipsum dolor.</div><!-- text-bg-success py-1 -->
      <div class="text-bg-success py-2">Lorem, ipsum dolor.</div><!-- text-bg-success py-2 -->
      <div class="text-bg-success py-3">Lorem, ipsum dolor.</div><!-- text-bg-success py-3 -->
      <div class="text-bg-success py-4">Lorem, ipsum dolor.</div><!-- text-bg-success py-4 -->
      <div class="text-bg-success py-5">Lorem, ipsum dolor.</div><!-- text-bg-success py-5 -->

      <!-- Padding Left & Right -->
      <div class="text-bg-danger my-1 px-1">Lorem, ipsum dolor.</div><!-- text-bg-danger my-1 px-1 -->
      <div class="text-bg-danger my-2 px-2">Lorem, ipsum dolor.</div><!-- text-bg-danger my-2 px-2 -->
      <div class="text-bg-danger my-3 px-3">Lorem, ipsum dolor.</div><!-- text-bg-danger my-3 px-3 -->
      <div class="text-bg-danger my-4 px-4">Lorem, ipsum dolor.</div><!-- text-bg-danger my-4 px-4 -->
      <div class="text-bg-danger my-5 px-5">Lorem, ipsum dolor.</div><!-- text-bg-danger my-5 px-5 -->

      <!-- Padding Top -->
      <div class="text-bg-info my-1 pt-1">Lorem, ipsum dolor.</div><!-- text-bg-info my-1 pt-1 -->
      <div class="text-bg-info my-2 pt-2">Lorem, ipsum dolor.</div><!-- text-bg-info my-2 pt-2 -->
      <div class="text-bg-info my-3 pt-3">Lorem, ipsum dolor.</div><!-- text-bg-info my-3 pt-3 -->
      <div class="text-bg-info my-4 pt-4">Lorem, ipsum dolor.</div><!-- text-bg-info my-4 pt-4 -->
      <div class="text-bg-info my-5 pt-5">Lorem, ipsum dolor.</div><!-- text-bg-info my-5 pt-5 -->

      <!-- Padding Bottom -->
      <div class="text-bg-warning my-1 pb-1">Lorem, ipsum dolor.</div><!-- text-bg-warning my-1 pb-1 -->
      <div class="text-bg-warning my-2 pb-2">Lorem, ipsum dolor.</div><!-- text-bg-warning my-2 pb-2 -->
      <div class="text-bg-warning my-3 pb-3">Lorem, ipsum dolor.</div><!-- text-bg-warning my-3 pb-3 -->
      <div class="text-bg-warning my-4 pb-4">Lorem, ipsum dolor.</div><!-- text-bg-warning my-4 pb-4 -->
      <div class="text-bg-warning my-5 pb-5">Lorem, ipsum dolor.</div><!-- text-bg-warning my-5 pb-5 -->

      <!-- Padding Left/Start -->
      <div class="text-bg-primary my-1 ps-1">Lorem, ipsum dolor.</div><!-- text-bg-primary my-1 ps-1 -->
      <div class="text-bg-primary my-2 ps-2">Lorem, ipsum dolor.</div><!-- text-bg-primary my-2 ps-2 -->
      <div class="text-bg-primary my-3 ps-3">Lorem, ipsum dolor.</div><!-- text-bg-primary my-3 ps-3 -->
      <div class="text-bg-primary my-4 ps-4">Lorem, ipsum dolor.</div><!-- text-bg-primary my-4 ps-4 -->
      <div class="text-bg-primary my-5 ps-5">Lorem, ipsum dolor.</div><!-- text-bg-primary my-5 ps-5 -->

      <!-- Padding Right/End -->
      <div class="text-bg-primary my-1 pe-1">Lorem, ipsum dolor.</div><!-- text-bg-primary my-1 pe-1 -->
      <div class="text-bg-primary my-2 pe-2">Lorem, ipsum dolor.</div><!-- text-bg-primary my-2 pe-2 -->
      <div class="text-bg-primary my-3 pe-3">Lorem, ipsum dolor.</div><!-- text-bg-primary my-3 pe-3 -->
      <div class="text-bg-primary my-4 pe-4">Lorem, ipsum dolor.</div><!-- text-bg-primary my-4 pe-4 -->
      <div class="text-bg-primary my-5 pe-5">Lorem, ipsum dolor.</div><!-- text-bg-primary my-5 pe-5 -->

      <!-- Stacks -->
      <div class="vstack gap-3">
        <div class="p-2 bg-info">First item</div>
        <div class="p-2 bg-info">Second item</div>
        <div class="p-2 bg-info">Third item</div>
      </div><!-- vstack gap-3 -->

      <div class="hstack gap-3">
        <div class="p-2 text-bg-success">First item</div>
        <div class="p-2 text-bg-success">Second item</div>
        <div class="p-2 text-bg-success">Third item</div>
      </div><!-- hstack gap-3 -->

      <!-- Don't go past here -->
    </div>
    <div style="margin-top: 350px"></div>

    <script src="./assets/js/bootstrap.bundle.min.js"></script>
  </body>
</html>
```
## Sizing, Borders and Shadows.
```HTML
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="./assets/css/bootstrap.min.css" />
    <title>Bootstrap Sandbox | Sizing, Borders & Shadows</title>
  </head>
  <body>
    <div class="container">
      <h1 class="mb-5">Sizing, Borders & Shadows</h1>

      <!-- Width -->
      <div class="bg-success text-white p-3 w-25">Width 25%</div>   <!-- bg-success text-white p-3 w-25 -->
      <div class="bg-success text-white p-3 w-50">Width 50%</div>   <!-- bg-success text-white p-3 w-50 -->
      <div class="bg-success text-white p-3 w-75">Width 75%</div>   <!-- bg-success text-white p-3 w-75 -->
      <div class="bg-success text-white p-3 w-100">Width 100%</div> <!-- bg-success text-white p-3 w-100 -->
      <div class="bg-success text-white p-3 w-auto">Width Auto</div><!-- bg-success text-white p-3 w-auto -->

      <br /><br />

      <!-- Height -->
      <div style="height: 300px; border: 1px solid #333">
        <div class="bg-primary text-white d-inline-block h-25">Height 25%</div>   <!-- bg-primary text-white d-inline-block h-25 -->
        <div class="bg-primary text-white d-inline-block h-50">Height 50%</div>   <!-- bg-primary text-white d-inline-block h-50 -->
        <div class="bg-primary text-white d-inline-block h-75">Height 75%</div>   <!-- bg-primary text-white d-inline-block h-75 -->
        <div class="bg-primary text-white d-inline-block h-100">Height 100%</div> <!-- bg-primary text-white d-inline-block h-100 -->
        <div class="bg-primary text-white d-inline-block h-auto">Height Auto</div><!-- bg-primary text-white d-inline-block h-auto -->
      </div>

      <br /><br />

      <!-- Borders -->
      <div class="p-3 mb-2 bg-light border border">Regular</div>             <!-- p-3 mb-2 bg-light border border -->
      <div class="p-3 mb-2 bg-light border border-top">Border Top</div>      <!-- p-3 mb-2 bg-light border border-top -->
      <div class="p-3 mb-2 bg-light border border-bottom">Border Bottom</div><!-- p-3 mb-2 bg-light border border-bottom -->
      <div class="p-3 mb-2 bg-light border border-start">Border Right</div>  <!-- p-3 mb-2 bg-light border border-start -->
      <div class="p-3 mb-2 bg-light border border-end">Border Left</div>     <!-- p-3 mb-2 bg-light border border-end -->

      <br /><br />

      <!-- Border Colors -->
      <div class="p-3 mb-2 bg-light border border-primary">Primary</div>    <!-- p-3 mb-2 bg-light border border-primary -->
      <div class="p-3 mb-2 bg-light border border-secondary">Secondary</div><!-- p-3 mb-2 bg-light border border-econdary -->
      <div class="p-3 mb-2 bg-light border border-success">Success</div>    <!-- p-3 mb-2 bg-light border border-success -->
      <div class="p-3 mb-2 bg-light border border-info">Info</div>          <!-- p-3 mb-2 bg-light border border-info -->
      <div class="p-3 mb-2 bg-light border border-warning">Warning</div>    <!-- p-3 mb-2 bg-light border border-warning -->
      <div class="p-3 mb-2 bg-light border border-danger">Danger</div>      <!-- p-3 mb-2 bg-light border border-danger -->
      <div class="p-3 mb-2 bg-light border border-light">Light</div>        <!-- p-3 mb-2 bg-light border border-light -->
      <div class="p-3 mb-2 bg-light border border-dark">Dark</div>          <!-- p-3 mb-2 bg-light border border-dark -->
      <div class="p-3 mb-2 bg-light border border-white">White</div>        <!-- p-3 mb-2 bg-light border border-white -->

      <br /><br />

      <!-- Border Radius -->
      <div class="p-3 mb-2 bg-light border rounded">Rounded</div>                   <!-- p-3 mb-2 bg-light border rounded -->
      <div class="p-3 mb-2 bg-light border rounded-top">Rounded Top</div>           <!-- p-3 mb-2 bg-light border rounded-top -->
      <div class="p-3 mb-2 bg-light border rounded-bottom">Rounded Bottom</div>     <!-- p-3 mb-2 bg-light border rounded-bottom -->
      <div class="p-3 mb-2 bg-light border rounded-end">Rounded Right</div>         <!-- p-3 mb-2 bg-light border rounded-end -->
      <div class="p-3 mb-2 bg-light border rounded-start">Rounded Left</div>        <!-- p-3 mb-2 bg-light border rounded-start -->
      <div class="p-3 mb-2 bg-light w-25 border rounded-circle">Rounded Circle</div><!-- p-3 mb-2 bg-light w-25 border rounded-circle -->
      <div class="p-3 mb-2 bg-light border rounded-1">Rounded 1</div>               <!-- p-3 mb-2 bg-light border rounded-1 -->
      <div class="p-3 mb-2 bg-light border rounded-2">Rounded 2</div>               <!-- p-3 mb-2 bg-light border rounded-2 -->
      <div class="p-3 mb-2 bg-light border rounded-3">Rounded 3</div>               <!-- p-3 mb-2 bg-light border rounded-3 -->
      <div class="p-3 mb-2 bg-light border rounded-4">Rounded 4</div>               <!-- p-3 mb-2 bg-light border rounded-4 -->
      <div class="p-3 mb-2 bg-light border rounded-5">Rounded 5</div>               <!-- p-3 mb-2 bg-light border rounded-5 -->

      <!-- Shadows -->
      <div class="p-3 mb-5 shadow-none">No shadow</div>      <!-- p-3 mb-5 shadow-none -->
      <div class="p-3 mb-5 shadow-sm">Small shadow</div>     <!-- p-3 mb-5 shadow-sm -->
      <div class="p-3 mb-5 shadow">Regular shadow</div>      <!-- p-3 mb-5 shadow -->
      <div class="p-3 mb-5 shadow-lg">Larger shadow</div>    <!-- p-3 mb-5 shadow-lg -->

      <!-- Don't go past here -->
    </div>
    <div style="margin-top: 350px"></div>

    <script src="./assets/js/bootstrap.bundle.min.js"></script>
  </body>
</html>
```
## Breakpoints.
![Default Breakpoints](./images/7-default-breakpoints.png)
```HTML
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="./assets/css/bootstrap.min.css" />
    <style>
      /*  X-Small devices (portrait phones, less than 576px) */
      body {
        background: gray;
      }

      /* `sm` applies to x-small devices (portrait phones, less than 576px) */
      @media (min-width: 576px ) {
        body{
          background: red;
        }
      }

      /* `md` applies to small devices (landscape phones, less than 768px) */
      @media (min-width: 768px) {
        body{
          background: blue;
        }
      }
      /* `lg` applies to medium devices (tablets, less than 992px) */
      @media (min-width: 991px) {
        body{
          background: green;
        }
      }
      /* `xl` applies to large devices (desktops, less than 1200px) */
      @media (min-width: 1199px) {
        body{
          background: yellow;
        }
      }
      /* `xxl` applies to x-large devices (large desktops, less than 1400px) */
      @media (min-width: 1399px) {
        body{
          background: purple;
        }
      }
    </style>
    <title>Bootstrap Sandbox | Breakpoints</title>
  </head>
  <body>
    <div class="container">
      <h1 class="mb-5">Breakpoints</h1>

      <!-- Don't go past here -->
    </div>
    <div style="margin-top: 350px"></div>

    <script src="./assets/js/bootstrap.bundle.min.js"></script>
  </body>
</html>
```
## Buttons
```HTML
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="./assets/css/bootstrap.min.css" />
    <title>Bootstrap Sandbox | Buttons</title>
  </head>
  <body>
    <div class="container">
      <h1 class="mb-5">Buttons</h1>

      <!-- Styles -->
      <button class="btn btn-primary">Primary</button>    <!-- btn btn-primary -->
      <button class="btn btn-secondary">Secondary</button><!-- btn btn-secondary -->
      <button class="btn btn-success">Success</button>    <!-- btn btn-success -->
      <button class="btn btn-danger">Danger</button>      <!-- btn btn-danger -->
      <button class="btn btn-warning">Warning</button>    <!-- btn btn-warning -->
      <button class="btn btn-info">Info</button>          <!-- btn btn-info -->
      <button class="btn btn-light">Light</button>        <!-- btn btn-light -->
      <button class="btn btn-dark">Dark</button>          <!-- btn btn-dark -->
      <button class="btn btn-link">Link</button>          <!-- btn btn-link -->

      <br /><br />

      <!-- Button Sizes -->
      <button class="btn btn-primary">Regular</button>     <!-- btn btn-primary -->
      <button class="btn btn-success btn-sm">Small</button><!-- btn btn-success btn-sm -->
      <button class="btn btn-danger btn-lg">Large</button> <!-- btn btn-danger btn-lg -->

      <br /><br />

      <!-- Button States -->
      <button class="btn btn-primary">Regular</button>          <!-- btn btn-primary -->
      <button class="btn btn-primary disabled">Disabled</button><!-- btn btn-primary disabled -->
      <button class="btn btn-primary active">Active</button>    <!-- btn btn-primary active -->

      <br /><br />

      <!-- Outline Buttons -->
      <button class="btn btn-outline-primary">Primary</button>    <!-- btn btn-outline-primary -->
      <button class="btn btn-outline-secondary">Secondary</button><!-- btn btn-outline-secondary -->
      <button class="btn btn-outline-success">Success</button>    <!-- btn btn-outline-success -->
      <button class="btn btn-outline-danger">Danger</button>      <!-- btn btn-outline-danger -->
      <button class="btn btn-outline-warning">Warning</button>    <!-- btn btn-outline-warning -->
      <button class="btn btn-outline-info">Info</button>          <!-- btn btn-outline-info -->
      <button class="btn btn-outline-light">Light</button>        <!-- btn btn-outline-light -->
      <button class="btn btn-outline-dark">Dark</button>          <!-- btn btn-outline-dark -->

      <br /><br />

      <!-- Links Formatted as Buttons -->
      <a href="#" class="btn btn-primary">Link Button</a>         <!-- btn btn-primary -->
      <a href="#" class="btn btn-primary btn-lg">Link Button</a>  <!-- btn btn-primary btn-lg -->
      <a href="#" class="btn btn-primary disabled">Link Button</a><!-- btn btn-primary disabled-->

      <br /><br />

      <!-- Block Buttons -->
      
      <div class="d-grid vstack gap-3"><!-- d-grid -->
        <button class="btn btn-primary">Submit</button>
        <button class="btn btn-danger">Cancel</button> 
      </div>

      <br /><br />

      <!-- Button Group -->
      <div class="btn-group hstack gap-3" role="group"><!-- class="btn-group hstack gap-3" role="group" -->
        <button class="btn btn-primary">Left</button>
        <button class="btn btn-secondary">Middle</button>
        <button class="btn btn-primary">Right</button>
      </div>

      <br /><br />

      <!-- Button Toolbar -->
      <div class="btn-toolbar" role="toolbar"><!-- class="btn- hstack gap-3" role="group" -->

        <div class="btn-group me-3" role="group">
          <button class="btn btn-primary">1</button>
          <button class="btn btn-secondary">2</button>
          <button class="btn btn-primary">3</button>
        </div>

        <div class="btn-group " role="group">
          <button class="btn btn-primary">4</button>
          <button class="btn btn-secondary">5</button>
          <button class="btn btn-primary">6</button>
        </div>
      </div>

       <br /><br />
     

      <!-- Dropdown Button -->
     <div class="dropdown"><!-- class="dropdown" -->

      <button class="btn btn-secondary dropdown-toggle" data-bs-toggle="dropdown">Dropdown Button</button><!-- class="dropdown-toggle" data-bs-toggle="dropdown" -->

      <ul class="dropdown-menu"><!-- class="dropdown-menu" -->
        <li><a href="#" class="dropdown-item">Link 1</a></li><!-- class="dropdown-item" -->
        <li><a href="#" class="dropdown-item">Link 2</a></li><!-- class="dropdown-item" -->
        <li><a href="#" class="dropdown-item">Link 3</a></li><!-- class="dropdown-item" -->
      </ul>
     </div>
      <!-- Don't go past here -->
    </div>
    <div style="margin-top: 350px"></div>

    <script src="./assets/js/bootstrap.bundle.min.js"></script>
  </body>
</html>
```
## Navbar.
```HTML
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="./assets/css/bootstrap.min.css" />
    <title>Bootstrap Sandbox | Navbar</title>
  </head>
  <body>
    <h1 class="mb-5">Navbar</h1>

    <!-- Simple Navbar -->
    <nav class="navbar navbar-expand-md bg-light"> <!-- class="navbar navbar-expand-md bg-light" -->

      <div class="container">                      <!-- class="container"-->
        <a href="#" class="navbar-brand">Navbar</a><!-- class="navbar-brand" -->

        <button type="button" 
        data-bs-toggle="collapse" 
        data-bs-target="#navbarNav"
        class="navbar-toggler">

      <!-- type="button" 
           data-bs-toggle="collapse" 
           data-bs-target="#navbarNav"
          class="navbar-toggler"-->

           <span class="navbar-toggler-icon"></span> <!-- class="navbar-toggler-icon" -->

        </button>
        <div class="collapse navbar-collapse" id="navbarNav"><!-- class="collapse" navbar-collapse id="navbarNav" -->

          <ul class="navbar-nav ms-auto"><!-- class="navbar-nav ms-auto" -->
            
              <li class="nav-item"><!-- class="nav-item"-->
                <a href="#" class="nav-link active">Home</a><!-- class="nav-link active"-->
              </li>
              <li class="nav-item"><!-- class="nav-item"-->
                <a href="#" class="nav-link active">About</a><!-- class="nav-link active"-->
              </li>
              <li class="nav-item"><!-- class="nav-item"-->
                <a href="#" class="nav-link active">Services</a><!-- class="nav-link active"-->
              </li>
              <li class="nav-item"><!-- class="nav-item"-->
                <a href="#" class="nav-link active">Contact</a><!-- class="nav-link active"-->
              </li>

          </ul>
        </div>
      </div>
    </nav>
    <br /><br />

    <!-- Color Variant -->
    <nav class="navbar navbar-expand-md bg-primary navbar-dark"> <!-- class="bg-dark || bg-xcolor navbar-dark" -->   
      <div class="container">                 
        <a href="#" class="navbar-brand">Navbar</a>
        <button type="button" 
        data-bs-toggle="collapse" 
        data-bs-target="#navbarNav"
        class="navbar-toggler">
           <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav ms-auto">
              <li class="nav-item">
                <a href="#" class="nav-link active">Home</a>
              </li>
              <li class="nav-item">
                <a href="#" class="nav-link active">About</a>
              </li>
              <li class="nav-item">
                <a href="#" class="nav-link active">Services</a>
              </li>
              <li class="nav-item">
                <a href="#" class="nav-link active">Contact</a>
              </li>

          </ul>
        </div>
      </div>
    </nav>

    <br /><br />

    <!-- Fixed Top -->
    <nav class="navbar navbar-expand-md fixed-top bg-dark navbar-dark"> <!-- class="fixed-top bg-dark navbar-dark" -->   
      <div class="container">                 
        <a href="#" class="navbar-brand">Navbar</a>
        <button type="button" 
        data-bs-toggle="collapse" 
        data-bs-target="#navbarNav"
        class="navbar-toggler">
           <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav ms-auto">
              <li class="nav-item">
                <a href="#" class="nav-link active">Home</a>
              </li>
              <li class="nav-item">
                <a href="#about"  class="nav-link active">About</a><!-- section link = href="#about"-->
              </li>
              <li class="nav-item">
                <a href="#" class="nav-link active">Services</a>
              </li>
              <li class="nav-item">
                <a href="#" class="nav-link active">Contact</a>
              </li>

          </ul>
        </div>
      </div>
    </nav>

    <!-- Form In Navbar -->
    <nav class="navbar navbar-expand-md bg-warning navbar-dark">    
      <div class="container">                 
        <a href="#" class="navbar-brand">Navbar</a>
        <form class="d-flex" role="search">            <!-- class="d-flex" role="search" -->
          <input type="text" class="form-control me-2"><!-- class="form-control me-2" -->
          <button class="btn btn-dark">Search</button>
        </form>
      </div>
    </nav>

    <br /><br />

    <p id="about"><!-- section link = href="#about"-->
      Lorem ipsum, dolor sit amet consectetur adipisicing elit. Fuga magni
      delectus libero eius necessitatibus. Aut quos eos ex non porro inventore
      minima, rerum magnam voluptate, ad doloremque fugiat perferendis obcaecati
      accusamus. Molestias voluptates tempore sed quae odit fuga culpa, quaerat
      ad! Dolores laudantium assumenda quas ipsum architecto necessitatibus,
      praesentium beatae, tenetur at facilis aliquam nisi illum labore earum
      corrupti dolorum corporis est deleniti cum pariatur, nemo officia? Porro
      corrupti accusantium soluta sed, minima ex voluptates neque nesciunt alias
      velit id itaque nulla nihil, rem eius! Blanditiis, veritatis rerum!
      Asperiores, excepturi in. Quibusdam repellat esse, soluta, sed excepturi
      tempora voluptas nihil voluptatem illo est quis. Quae at possimus aut
      nostrum nam quo nulla nesciunt molestias dolore eum! Ipsum, temporibus!
      Ducimus maiores fuga eligendi eum mollitia. Eius nobis explicabo
      distinctio, quia necessitatibus perspiciatis nihil, id delectus ipsa
      officia dolore sit rerum molestias pariatur. Sunt dignissimos iste facilis
      sit nulla adipisci laudantium rem. At dolorum exercitationem voluptates
      consequatur, aperiam inventore mollitia minus voluptatibus perferendis
      laboriosam totam doloribus sequi molestiae maxime harum sed ex eos modi
      consectetur perspiciatis, similique culpa corrupti eum iste? Laboriosam
      laudantium dicta quia nisi. Aliquam molestias, quo soluta nisi eos beatae!
      Hic reprehenderit quasi atque facere deleniti voluptatem necessitatibus
      velit aperiam consectetur, similique optio quisquam praesentium officia
      corporis ad neque saepe aspernatur voluptas fugit nostrum error esse,
      iusto quidem tempore? Voluptate nulla perferendis minima amet quaerat
      nobis! Placeat, quam voluptate labore quasi pariatur repudiandae animi,
      ipsum cum earum, at aperiam ullam nostrum impedit obcaecati perspiciatis.
      Dignissimos odit, velit, ratione voluptates dolor modi esse accusantium
      autem facilis nostrum molestias fugit nihil quisquam, dolorem deserunt.
      Veniam, dicta necessitatibus sequi expedita molestias alias asperiores,
      temporibus quo aliquid corrupti atque, sapiente est explicabo eos dolorum
      maiores sit omnis ut adipisci culpa. Nulla cumque, consequatur dicta amet
      laboriosam velit voluptatum porro nisi facere? Nulla dolore quae non iure?
      Aliquam similique dicta cumque deleniti mollitia totam iusto dolorum!
      Cupiditate adipisci repellendus maiores? Rerum maxime soluta culpa ad non
      asperiores facere explicabo maiores iste, vitae ducimus laboriosam!
      Aliquid, quos quasi, iure rerum enim ipsa maiores illo unde ipsum dicta
      necessitatibus deserunt sunt laborum beatae tempora eius consequatur
      quaerat voluptatem adipisci amet aperiam magnam! Doloribus ex, tenetur
      saepe facere tempore voluptatem rerum aliquid inventore ea error similique
      natus sit enim aperiam officia esse est numquam quae repudiandae. Esse
      aliquid cupiditate nam itaque impedit eveniet, tempore ipsum officiis
      tenetur quam quae, a assumenda architecto voluptates ad pariatur facere
      magnam fugiat. Ex exercitationem quidem quibusdam, reprehenderit non quos,
      laborum quaerat porro eveniet impedit, excepturi sed aspernatur libero est
      cupiditate repellendus placeat explicabo quisquam itaque similique. Velit
      ullam quidem ratione hic suscipit quae, libero dolor porro? Impedit, hic
      quae. Dolores, exercitationem quaerat nesciunt sapiente maiores molestias
      fugiat pariatur dolor, maxime ut libero ea odio velit consequatur. Aut,
      numquam repellat! Perferendis reprehenderit consequuntur ipsum hic error
      fugiat corrupti eaque! Omnis adipisci ducimus obcaecati. Deleniti id
      distinctio voluptatum quisquam quo odit quae amet laboriosam dolorem
      corporis quam quasi reprehenderit perferendis ullam qui placeat, eius,
      omnis dolores ut fuga unde fugit. Suscipit, asperiores modi?
    </p>

    <div id="about">
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Molestias sit
      repellendus error culpa odit debitis reprehenderit nesciunt dolores nihil
      soluta distinctio, magni exercitationem in corporis iusto illo? Veniam,
      omnis sit.
    </div>

    <script src="./assets/js/bootstrap.bundle.min.js"></script>
  </body>
</html>
```
## Dark Mode & Variables.
[CSS Variables](https://getbootstrap.com/docs/5.3/customize/css-variables/)
```HTML
<!DOCTYPE html>
<html lang="en" data-bs-theme="dark"><!-- data-bs-theme="dark" -->
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="./assets/css/bootstrap.min.css" />
    <style>
      body{
        background: var(--bs-primary);
      }
    </style>
    <title>Bootstrap Sandbox | Dark Mode</title>
  </head>
  <body>
    <div class="container">
      <h1 class="mb-5">Dark Mode</h1>

      <div class="card" style="width: 18rem">
        <div class="card-header">This is a card</div>
        <div class="card-body">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempora,
          voluptas.
        </div>
      </div>
      <div class="card" style="width: 18rem" data-bs-theme="light"><!--  data-bs-theme="light" -->
        <div class="card-header">This is a card</div>
        <div class="card-body">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempora,
          voluptas.
        </div>
      </div>
      <!-- Don't go past here -->
    </div>
    
    <div style="margin-top: 350px"></div>

    <script src="./assets/js/bootstrap.bundle.min.js"></script>
  </body>
</html>
```


