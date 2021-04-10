





<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
  <link rel="dns-prefetch" href="https://github.githubassets.com">
  <link rel="dns-prefetch" href="https://avatars0.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars1.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars2.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars3.githubusercontent.com">
  <link rel="dns-prefetch" href="https://github-cloud.s3.amazonaws.com">
  <link rel="dns-prefetch" href="https://user-images.githubusercontent.com/">



  <link crossorigin="anonymous" media="all" integrity="sha512-lEwNhIgWxFtdGboTlCciWWGiX2vG3LOojEE671oRJEhnPj6jpmgQTJtpq3O2KBzCcln6RzwfvHlyFaI/oR+RNQ==" rel="stylesheet" href="https://github.githubassets.com/assets/frameworks-849637ecbd4bd65815cc113d80fee2d4.css" />
  <link crossorigin="anonymous" media="all" integrity="sha512-J91Qhea0f13DaSjx3AXXGO3viFpQAPPnpVDE8Umc73sXEtrah52Hq277J1yN+ALwl/RwH5VQ/Ntc0756LZy/7w==" rel="stylesheet" href="https://github.githubassets.com/assets/site-d20aa35917cf810095fab7458ea2a8e4.css" />
    <link crossorigin="anonymous" media="all" integrity="sha512-nbXfO4fh1nahyjggjTnpWxGoA7FoTdx2f21d62JQeVn0RlLoYci8FX3fuqk4Sn/kD8Yuzgd/IHXroBMoxFLFWA==" rel="stylesheet" href="https://github.githubassets.com/assets/github-8fec968b4bdafcef25940c968feaf09b.css" />
    
    
    
    

  <meta name="viewport" content="width=device-width">
  
  <title>peewee/query_examples.rst at master · coleifer/peewee · GitHub</title>
    <meta name="description" content="a small, expressive orm -- supports postgresql, mysql and sqlite - coleifer/peewee">
    <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">
  <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
  <meta property="fb:app_id" content="1401488693436528">

    <meta name="twitter:image:src" content="https://avatars0.githubusercontent.com/u/119974?s=400&amp;v=4" /><meta name="twitter:site" content="@github" /><meta name="twitter:card" content="summary" /><meta name="twitter:title" content="coleifer/peewee" /><meta name="twitter:description" content="a small, expressive orm -- supports postgresql, mysql and sqlite - coleifer/peewee" />
    <meta property="og:image" content="https://avatars0.githubusercontent.com/u/119974?s=400&amp;v=4" /><meta property="og:site_name" content="GitHub" /><meta property="og:type" content="object" /><meta property="og:title" content="coleifer/peewee" /><meta property="og:url" content="https://github.com/coleifer/peewee" /><meta property="og:description" content="a small, expressive orm -- supports postgresql, mysql and sqlite - coleifer/peewee" />

  <link rel="assets" href="https://github.githubassets.com/">
  
  <meta name="pjax-timeout" content="1000">
  
  <meta name="request-id" content="D335:7880:6505C:D307D:5D8D3894" data-pjax-transient>


  

  <meta name="selected-link" value="repo_source" data-pjax-transient>

      <meta name="google-site-verification" content="KT5gs8h0wvaagLKAVWq8bbeNwnZZK1r1XQysX3xurLU">
    <meta name="google-site-verification" content="ZzhVyEFwb7w3e0-uOTltm8Jsck2F5StVihD0exw2fsA">
    <meta name="google-site-verification" content="GXs5KoUUkNCoaAZn7wPN-t01Pywp9M3sEjnt_3_ZWPc">

  <meta name="octolytics-host" content="collector.githubapp.com" /><meta name="octolytics-app-id" content="github" /><meta name="octolytics-event-url" content="https://collector.githubapp.com/github-external/browser_event" /><meta name="octolytics-dimension-request_id" content="D335:7880:6505C:D307D:5D8D3894" /><meta name="octolytics-dimension-region_edge" content="iad" /><meta name="octolytics-dimension-region_render" content="iad" /><meta name="octolytics-dimension-ga_id" content="" class="js-octo-ga-id" /><meta name="octolytics-dimension-visitor_id" content="2133105971668269204" />
<meta name="analytics-location" content="/&lt;user-name&gt;/&lt;repo-name&gt;/blob/show" data-pjax-transient="true" />



    <meta name="google-analytics" content="UA-3769691-2">


<meta class="js-ga-set" name="dimension1" content="Logged Out">



  

      <meta name="hostname" content="github.com">
    <meta name="user-login" content="">

      <meta name="expected-hostname" content="github.com">
    <meta name="js-proxy-site-detection-payload" content="M2M5ZjZjM2VhNWM2MzNkZmNlODVlZTYwMWY3NDUxZDI5ZTM3ZThlMjBkMzlkYzQxZjg1OTI3ZTVlMzE0MmU4Nnx7InJlbW90ZV9hZGRyZXNzIjoiMTY4LjE0OS4xNDQuNDAiLCJyZXF1ZXN0X2lkIjoiRDMzNTo3ODgwOjY1MDVDOkQzMDdEOjVEOEQzODk0IiwidGltZXN0YW1wIjoxNTY5NTM2MTQ4LCJob3N0IjoiZ2l0aHViLmNvbSJ9">

    <meta name="enabled-features" content="ACTIONS_V2_ON_MARKETPLACE,MARKETPLACE_FEATURED_BLOG_POSTS,MARKETPLACE_INVOICED_BILLING,MARKETPLACE_SOCIAL_PROOF_CUSTOMERS,MARKETPLACE_TRENDING_SOCIAL_PROOF,MARKETPLACE_RECOMMENDATIONS,MARKETPLACE_PENDING_INSTALLATIONS">

  <meta name="html-safe-nonce" content="e9a6d174f33d26beb0c9a8997690656f33183fe8">

  <meta http-equiv="x-pjax-version" content="f192b7601f8af68a4d8b54d04110f52a">
  

      <link href="https://github.com/coleifer/peewee/commits/master.atom" rel="alternate" title="Recent Commits to peewee:master" type="application/atom+xml">

  <meta name="go-import" content="github.com/coleifer/peewee git https://github.com/coleifer/peewee.git">

  <meta name="octolytics-dimension-user_id" content="119974" /><meta name="octolytics-dimension-user_login" content="coleifer" /><meta name="octolytics-dimension-repository_id" content="979480" /><meta name="octolytics-dimension-repository_nwo" content="coleifer/peewee" /><meta name="octolytics-dimension-repository_public" content="true" /><meta name="octolytics-dimension-repository_is_fork" content="false" /><meta name="octolytics-dimension-repository_network_root_id" content="979480" /><meta name="octolytics-dimension-repository_network_root_nwo" content="coleifer/peewee" /><meta name="octolytics-dimension-repository_explore_github_marketplace_ci_cta_shown" content="false" />


    <link rel="canonical" href="https://github.com/coleifer/peewee/blob/master/docs/peewee/query_examples.rst" data-pjax-transient>


  <meta name="browser-stats-url" content="https://api.github.com/_private/browser/stats">

  <meta name="browser-errors-url" content="https://api.github.com/_private/browser/errors">

  <link rel="mask-icon" href="https://github.githubassets.com/pinned-octocat.svg" color="#000000">
  <link rel="icon" type="image/x-icon" class="js-site-favicon" href="https://github.githubassets.com/favicon.ico">

<meta name="theme-color" content="#1e2327">





  <link rel="manifest" href="/manifest.json" crossOrigin="use-credentials">

  </head>

  <body class="logged-out env-production page-responsive page-blob">
    

  <div class="position-relative js-header-wrapper ">
    <a href="#start-of-content" tabindex="1" class="px-2 py-4 bg-blue text-white show-on-focus js-skip-to-content">Skip to content</a>
    <div id="js-pjax-loader-bar" class="pjax-loader-bar"><div class="progress"></div></div>

    
    
    


        <header class="Header-old header-logged-out js-details-container Details position-relative f4 py-2" role="banner">
  <div class="container-lg d-lg-flex flex-items-center p-responsive">
    <div class="d-flex flex-justify-between flex-items-center">
        <a class="mr-4" href="https://github.com/" aria-label="Homepage" data-ga-click="(Logged out) Header, go to homepage, icon:logo-wordmark">
          <svg height="32" class="octicon octicon-mark-github text-white" viewBox="0 0 16 16" version="1.1" width="32" aria-hidden="true"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"/></svg>
        </a>

          <div class="d-lg-none css-truncate css-truncate-target width-fit p-2">
            
              <svg class="octicon octicon-repo" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
    <a class="Header-link" href="/coleifer">coleifer</a>
    /
    <a class="Header-link" href="/coleifer/peewee">peewee</a>


          </div>

        <div class="d-flex flex-items-center">
            <a href="/join?source=header-repo"
              class="d-inline-block d-lg-none f5 text-white no-underline border border-gray-dark rounded-2 px-2 py-1 mr-3 mr-sm-5"
              data-hydro-click="{&quot;event_type&quot;:&quot;authentication.click&quot;,&quot;payload&quot;:{&quot;location_in_page&quot;:&quot;site header&quot;,&quot;repository_id&quot;:null,&quot;auth_type&quot;:&quot;SIGN_UP&quot;,&quot;client_id&quot;:null,&quot;originating_request_id&quot;:&quot;D335:7880:6505C:D307D:5D8D3894&quot;,&quot;originating_url&quot;:&quot;https://github.com/coleifer/peewee/blob/master/docs/peewee/query_examples.rst&quot;,&quot;referrer&quot;:null,&quot;user_id&quot;:null}}" data-hydro-click-hmac="1f9ef421072e7bd6ed6e31cfe5161de353d6ca5e1c9b9e29825f0ba5901e165d"
              data-ga-click="(Logged out) Header, clicked Sign up, text:sign-up">
              Sign&nbsp;up
            </a>

          <button class="btn-link d-lg-none mt-1 js-details-target" type="button" aria-label="Toggle navigation" aria-expanded="false">
            <svg height="24" class="octicon octicon-three-bars text-white" viewBox="0 0 12 16" version="1.1" width="18" aria-hidden="true"><path fill-rule="evenodd" d="M11.41 9H.59C0 9 0 8.59 0 8c0-.59 0-1 .59-1H11.4c.59 0 .59.41.59 1 0 .59 0 1-.59 1h.01zm0-4H.59C0 5 0 4.59 0 4c0-.59 0-1 .59-1H11.4c.59 0 .59.41.59 1 0 .59 0 1-.59 1h.01zM.59 11H11.4c.59 0 .59.41.59 1 0 .59 0 1-.59 1H.59C0 13 0 12.59 0 12c0-.59 0-1 .59-1z"/></svg>
          </button>
        </div>
    </div>

    <div class="HeaderMenu HeaderMenu--logged-out position-fixed top-0 right-0 bottom-0 height-fit position-lg-relative d-lg-flex flex-justify-between flex-items-center flex-auto">
      <div class="d-flex d-lg-none flex-justify-end border-bottom bg-gray-light p-3">
        <button class="btn-link js-details-target" type="button" aria-label="Toggle navigation" aria-expanded="false">
          <svg height="24" class="octicon octicon-x text-gray" viewBox="0 0 12 16" version="1.1" width="18" aria-hidden="true"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"/></svg>
        </button>
      </div>

        <nav class="mt-0 px-3 px-lg-0 mb-5 mb-lg-0" aria-label="Global">
          <ul class="d-lg-flex list-style-none">
              <li class="d-block d-lg-flex flex-lg-nowrap flex-lg-items-center border-bottom border-lg-bottom-0 mr-0 mr-lg-3 edge-item-fix position-relative flex-wrap flex-justify-between d-flex flex-items-center ">
                <details class="HeaderMenu-details details-overlay details-reset width-full">
                  <summary class="HeaderMenu-summary HeaderMenu-link px-0 py-3 border-0 no-wrap d-block d-lg-inline-block">
                    Why GitHub?
                    <svg x="0px" y="0px" viewBox="0 0 14 8" xml:space="preserve" fill="none" class="icon-chevon-down-mktg position-absolute position-lg-relative">
                      <path d="M1,1l6.2,6L13,1"></path>
                    </svg>
                  </summary>
                  <div class="dropdown-menu flex-auto rounded-1 bg-white px-0 mt-0 pb-4 p-lg-4 position-relative position-lg-absolute left-0 left-lg-n4">
                    <a href="/features" class="py-2 lh-condensed-ultra d-block link-gray-dark no-underline h5 Bump-link--hover" data-ga-click="(Logged out) Header, go to Features">Features <span class="Bump-link-symbol float-right text-normal text-gray-light">&rarr;</span></a>
                    <ul class="list-style-none f5 pb-3">
                      <li class="edge-item-fix"><a href="/features/code-review/" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Code review">Code review</a></li>
                      <li class="edge-item-fix"><a href="/features/project-management/" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Project management">Project management</a></li>
                      <li class="edge-item-fix"><a href="/features/integrations" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Integrations">Integrations</a></li>
                      <li class="edge-item-fix"><a href="/features/actions" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Actions">Actions</a>
                          <li class="edge-item-fix"><a href="/features/package-registry" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Package Registry">Package registry</a>

                          <li class="edge-item-fix"><a href="/features/security" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Security">Security</a>

                      <li class="edge-item-fix"><a href="/features#team-management" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Team management">Team management</a></li>
                      <li class="edge-item-fix"><a href="/features#social-coding" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Social coding">Social coding</a></li>
                      <li class="edge-item-fix"><a href="/features#documentation" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Documentation">Documentation</a></li>
                      <li class="edge-item-fix"><a href="/features#code-hosting" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Code hosting">Code hosting</a></li>
                    </ul>

                    <ul class="list-style-none mb-0 border-lg-top pt-lg-3">
                      <li class="edge-item-fix"><a href="/customer-stories" class="py-2 lh-condensed-ultra d-block no-underline link-gray-dark no-underline h5 Bump-link--hover" data-ga-click="(Logged out) Header, go to Customer stories">Customer stories <span class="Bump-link-symbol float-right text-normal text-gray-light">&rarr;</span></a></li>
                      <li class="edge-item-fix"><a href="/security" class="py-2 lh-condensed-ultra d-block no-underline link-gray-dark no-underline h5 Bump-link--hover" data-ga-click="(Logged out) Header, go to Security">Security <span class="Bump-link-symbol float-right text-normal text-gray-light">&rarr;</span></a></li>
                    </ul>
                  </div>
                </details>
              </li>
              <li class="border-bottom border-lg-bottom-0 mr-0 mr-lg-3">
                <a href="/enterprise" class="HeaderMenu-link no-underline py-3 d-block d-lg-inline-block" data-ga-click="(Logged out) Header, go to Enterprise">Enterprise</a>
              </li>

              <li class="d-block d-lg-flex flex-lg-nowrap flex-lg-items-center border-bottom border-lg-bottom-0 mr-0 mr-lg-3 edge-item-fix position-relative flex-wrap flex-justify-between d-flex flex-items-center ">
                <details class="HeaderMenu-details details-overlay details-reset width-full">
                  <summary class="HeaderMenu-summary HeaderMenu-link px-0 py-3 border-0 no-wrap d-block d-lg-inline-block">
                    Explore
                    <svg x="0px" y="0px" viewBox="0 0 14 8" xml:space="preserve" fill="none" class="icon-chevon-down-mktg position-absolute position-lg-relative">
                      <path d="M1,1l6.2,6L13,1"></path>
                    </svg>
                  </summary>

                  <div class="dropdown-menu flex-auto rounded-1 bg-white px-0 pt-2 pb-0 mt-0 pb-4 p-lg-4 position-relative position-lg-absolute left-0 left-lg-n4">
                    <ul class="list-style-none mb-3">
                      <li class="edge-item-fix"><a href="/explore" class="py-2 lh-condensed-ultra d-block link-gray-dark no-underline h5 Bump-link--hover" data-ga-click="(Logged out) Header, go to Explore">Explore GitHub <span class="Bump-link-symbol float-right text-normal text-gray-light">&rarr;</span></a></li>
                    </ul>

                    <h4 class="text-gray-light text-normal text-mono f5 mb-2 border-lg-top pt-lg-3">Learn &amp; contribute</h4>
                    <ul class="list-style-none mb-3">
                      <li class="edge-item-fix"><a href="/topics" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Topics">Topics</a></li>
                        <li class="edge-item-fix"><a href="/collections" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Collections">Collections</a></li>
                      <li class="edge-item-fix"><a href="/trending" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Trending">Trending</a></li>
                      <li class="edge-item-fix"><a href="https://lab.github.com/" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Learning lab">Learning Lab</a></li>
                      <li class="edge-item-fix"><a href="https://opensource.guide" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Open source guides">Open source guides</a></li>
                    </ul>

                    <h4 class="text-gray-light text-normal text-mono f5 mb-2 border-lg-top pt-lg-3">Connect with others</h4>
                    <ul class="list-style-none mb-0">
                      <li class="edge-item-fix"><a href="https://github.com/events" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Events">Events</a></li>
                      <li class="edge-item-fix"><a href="https://github.community" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Community forum">Community forum</a></li>
                      <li class="edge-item-fix"><a href="https://education.github.com" class="py-2 pb-0 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to GitHub Education">GitHub Education</a></li>
                    </ul>
                  </div>
                </details>
              </li>

              <li class="border-bottom border-lg-bottom-0 mr-0 mr-lg-3">
                <a href="/marketplace" class="HeaderMenu-link no-underline py-3 d-block d-lg-inline-block" data-ga-click="(Logged out) Header, go to Marketplace">Marketplace</a>
              </li>

              <li class="d-block d-lg-flex flex-lg-nowrap flex-lg-items-center border-bottom border-lg-bottom-0 mr-0 mr-lg-3 edge-item-fix position-relative flex-wrap flex-justify-between d-flex flex-items-center ">
                <details class="HeaderMenu-details details-overlay details-reset width-full">
                  <summary class="HeaderMenu-summary HeaderMenu-link px-0 py-3 border-0 no-wrap d-block d-lg-inline-block">
                    Pricing
                    <svg x="0px" y="0px" viewBox="0 0 14 8" xml:space="preserve" fill="none" class="icon-chevon-down-mktg position-absolute position-lg-relative">
                       <path d="M1,1l6.2,6L13,1"></path>
                    </svg>
                  </summary>

                  <div class="dropdown-menu flex-auto rounded-1 bg-white px-0 pt-2 pb-4 mt-0 p-lg-4 position-relative position-lg-absolute left-0 left-lg-n4">
                    <a href="/pricing" class="pb-2 lh-condensed-ultra d-block link-gray-dark no-underline h5 Bump-link--hover" data-ga-click="(Logged out) Header, go to Pricing">Plans <span class="Bump-link-symbol float-right text-normal text-gray-light">&rarr;</span></a>

                    <ul class="list-style-none mb-3">
                      <li class="edge-item-fix"><a href="/pricing#feature-comparison" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Compare plans">Compare plans</a></li>
                      <li class="edge-item-fix"><a href="https://enterprise.github.com/contact" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Contact Sales">Contact Sales</a></li>
                    </ul>

                    <ul class="list-style-none mb-0 border-lg-top pt-lg-3">
                      <li class="edge-item-fix"><a href="/nonprofit" class="py-2 lh-condensed-ultra d-block no-underline link-gray-dark no-underline h5 Bump-link--hover" data-ga-click="(Logged out) Header, go to Nonprofits">Nonprofit <span class="Bump-link-symbol float-right text-normal text-gray-light">&rarr;</span></a></li>
                      <li class="edge-item-fix"><a href="https://education.github.com" class="py-2 pb-0 lh-condensed-ultra d-block no-underline link-gray-dark no-underline h5 Bump-link--hover"  data-ga-click="(Logged out) Header, go to Education">Education <span class="Bump-link-symbol float-right text-normal text-gray-light">&rarr;</span></a></li>
                    </ul>
                  </div>
                </details>
              </li>
          </ul>
        </nav>

      <div class="d-lg-flex flex-items-center px-3 px-lg-0 text-center text-lg-left">
          <div class="d-lg-flex mb-3 mb-lg-0">
            <div class="header-search flex-self-stretch flex-lg-self-auto mr-0 mr-lg-3 mb-3 mb-lg-0 scoped-search site-scoped-search js-site-search position-relative js-jump-to"
  role="combobox"
  aria-owns="jump-to-results"
  aria-label="Search or jump to"
  aria-haspopup="listbox"
  aria-expanded="false"
>
  <div class="position-relative">
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="js-site-search-form" role="search" aria-label="Site" data-scope-type="Repository" data-scope-id="979480" data-scoped-search-url="/coleifer/peewee/search" data-unscoped-search-url="/search" action="/coleifer/peewee/search" accept-charset="UTF-8" method="get"><input name="utf8" type="hidden" value="&#x2713;" />
      <label class="form-control input-sm header-search-wrapper p-0 header-search-wrapper-jump-to position-relative d-flex flex-justify-between flex-items-center js-chromeless-input-container">
        <input type="text"
          class="form-control input-sm header-search-input jump-to-field js-jump-to-field js-site-search-focus js-site-search-field is-clearable"
          data-hotkey="s,/"
          name="q"
          value=""
          placeholder="Search"
          data-unscoped-placeholder="Search GitHub"
          data-scoped-placeholder="Search"
          autocapitalize="off"
          aria-autocomplete="list"
          aria-controls="jump-to-results"
          aria-label="Search"
          data-jump-to-suggestions-path="/_graphql/GetSuggestedNavigationDestinations#csrf-token=M57YSMBKFNnhG9Jo7EvibcnQTXx2+RQ//2dWQkn/D/VCu1DMfBmJHxAaC1B1XnNljsoWKV78E8aHO9cvGmwtoA=="
          spellcheck="false"
          autocomplete="off"
          >
          <input type="hidden" class="js-site-search-type-field" name="type" >
            <img src="https://github.githubassets.com/images/search-key-slash.svg" alt="" class="mr-2 header-search-key-slash">

            <div class="Box position-absolute overflow-hidden d-none jump-to-suggestions js-jump-to-suggestions-container">
              
<ul class="d-none js-jump-to-suggestions-template-container">
  

<li class="d-flex flex-justify-start flex-items-center p-0 f5 navigation-item js-navigation-item js-jump-to-suggestion" role="option">
  <a tabindex="-1" class="no-underline d-flex flex-auto flex-items-center jump-to-suggestions-path js-jump-to-suggestion-path js-navigation-open p-2" href="">
    <div class="jump-to-octicon js-jump-to-octicon flex-shrink-0 mr-2 text-center d-none">
      <svg height="16" width="16" class="octicon octicon-repo flex-shrink-0 js-jump-to-octicon-repo d-none" title="Repository" aria-label="Repository" viewBox="0 0 12 16" version="1.1" role="img"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-project flex-shrink-0 js-jump-to-octicon-project d-none" title="Project" aria-label="Project" viewBox="0 0 15 16" version="1.1" role="img"><path fill-rule="evenodd" d="M10 12h3V2h-3v10zm-4-2h3V2H6v8zm-4 4h3V2H2v12zm-1 1h13V1H1v14zM14 0H1a1 1 0 0 0-1 1v14a1 1 0 0 0 1 1h13a1 1 0 0 0 1-1V1a1 1 0 0 0-1-1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-search flex-shrink-0 js-jump-to-octicon-search d-none" title="Search" aria-label="Search" viewBox="0 0 16 16" version="1.1" role="img"><path fill-rule="evenodd" d="M15.7 13.3l-3.81-3.83A5.93 5.93 0 0 0 13 6c0-3.31-2.69-6-6-6S1 2.69 1 6s2.69 6 6 6c1.3 0 2.48-.41 3.47-1.11l3.83 3.81c.19.2.45.3.7.3.25 0 .52-.09.7-.3a.996.996 0 0 0 0-1.41v.01zM7 10.7c-2.59 0-4.7-2.11-4.7-4.7 0-2.59 2.11-4.7 4.7-4.7 2.59 0 4.7 2.11 4.7 4.7 0 2.59-2.11 4.7-4.7 4.7z"/></svg>
    </div>

    <img class="avatar mr-2 flex-shrink-0 js-jump-to-suggestion-avatar d-none" alt="" aria-label="Team" src="" width="28" height="28">

    <div class="jump-to-suggestion-name js-jump-to-suggestion-name flex-auto overflow-hidden text-left no-wrap css-truncate css-truncate-target">
    </div>

    <div class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none js-jump-to-badge-search">
      <span class="js-jump-to-badge-search-text-default d-none" aria-label="in this repository">
        In this repository
      </span>
      <span class="js-jump-to-badge-search-text-global d-none" aria-label="in all of GitHub">
        All GitHub
      </span>
      <span aria-hidden="true" class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>

    <div aria-hidden="true" class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none d-on-nav-focus js-jump-to-badge-jump">
      Jump to
      <span class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>
  </a>
</li>

</ul>

<ul class="d-none js-jump-to-no-results-template-container">
  <li class="d-flex flex-justify-center flex-items-center f5 d-none js-jump-to-suggestion p-2">
    <span class="text-gray">No suggested jump to results</span>
  </li>
</ul>

<ul id="jump-to-results" role="listbox" class="p-0 m-0 js-navigation-container jump-to-suggestions-results-container js-jump-to-suggestions-results-container">
  

<li class="d-flex flex-justify-start flex-items-center p-0 f5 navigation-item js-navigation-item js-jump-to-scoped-search d-none" role="option">
  <a tabindex="-1" class="no-underline d-flex flex-auto flex-items-center jump-to-suggestions-path js-jump-to-suggestion-path js-navigation-open p-2" href="">
    <div class="jump-to-octicon js-jump-to-octicon flex-shrink-0 mr-2 text-center d-none">
      <svg height="16" width="16" class="octicon octicon-repo flex-shrink-0 js-jump-to-octicon-repo d-none" title="Repository" aria-label="Repository" viewBox="0 0 12 16" version="1.1" role="img"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-project flex-shrink-0 js-jump-to-octicon-project d-none" title="Project" aria-label="Project" viewBox="0 0 15 16" version="1.1" role="img"><path fill-rule="evenodd" d="M10 12h3V2h-3v10zm-4-2h3V2H6v8zm-4 4h3V2H2v12zm-1 1h13V1H1v14zM14 0H1a1 1 0 0 0-1 1v14a1 1 0 0 0 1 1h13a1 1 0 0 0 1-1V1a1 1 0 0 0-1-1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-search flex-shrink-0 js-jump-to-octicon-search d-none" title="Search" aria-label="Search" viewBox="0 0 16 16" version="1.1" role="img"><path fill-rule="evenodd" d="M15.7 13.3l-3.81-3.83A5.93 5.93 0 0 0 13 6c0-3.31-2.69-6-6-6S1 2.69 1 6s2.69 6 6 6c1.3 0 2.48-.41 3.47-1.11l3.83 3.81c.19.2.45.3.7.3.25 0 .52-.09.7-.3a.996.996 0 0 0 0-1.41v.01zM7 10.7c-2.59 0-4.7-2.11-4.7-4.7 0-2.59 2.11-4.7 4.7-4.7 2.59 0 4.7 2.11 4.7 4.7 0 2.59-2.11 4.7-4.7 4.7z"/></svg>
    </div>

    <img class="avatar mr-2 flex-shrink-0 js-jump-to-suggestion-avatar d-none" alt="" aria-label="Team" src="" width="28" height="28">

    <div class="jump-to-suggestion-name js-jump-to-suggestion-name flex-auto overflow-hidden text-left no-wrap css-truncate css-truncate-target">
    </div>

    <div class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none js-jump-to-badge-search">
      <span class="js-jump-to-badge-search-text-default d-none" aria-label="in this repository">
        In this repository
      </span>
      <span class="js-jump-to-badge-search-text-global d-none" aria-label="in all of GitHub">
        All GitHub
      </span>
      <span aria-hidden="true" class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>

    <div aria-hidden="true" class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none d-on-nav-focus js-jump-to-badge-jump">
      Jump to
      <span class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>
  </a>
</li>

  

<li class="d-flex flex-justify-start flex-items-center p-0 f5 navigation-item js-navigation-item js-jump-to-global-search d-none" role="option">
  <a tabindex="-1" class="no-underline d-flex flex-auto flex-items-center jump-to-suggestions-path js-jump-to-suggestion-path js-navigation-open p-2" href="">
    <div class="jump-to-octicon js-jump-to-octicon flex-shrink-0 mr-2 text-center d-none">
      <svg height="16" width="16" class="octicon octicon-repo flex-shrink-0 js-jump-to-octicon-repo d-none" title="Repository" aria-label="Repository" viewBox="0 0 12 16" version="1.1" role="img"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-project flex-shrink-0 js-jump-to-octicon-project d-none" title="Project" aria-label="Project" viewBox="0 0 15 16" version="1.1" role="img"><path fill-rule="evenodd" d="M10 12h3V2h-3v10zm-4-2h3V2H6v8zm-4 4h3V2H2v12zm-1 1h13V1H1v14zM14 0H1a1 1 0 0 0-1 1v14a1 1 0 0 0 1 1h13a1 1 0 0 0 1-1V1a1 1 0 0 0-1-1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-search flex-shrink-0 js-jump-to-octicon-search d-none" title="Search" aria-label="Search" viewBox="0 0 16 16" version="1.1" role="img"><path fill-rule="evenodd" d="M15.7 13.3l-3.81-3.83A5.93 5.93 0 0 0 13 6c0-3.31-2.69-6-6-6S1 2.69 1 6s2.69 6 6 6c1.3 0 2.48-.41 3.47-1.11l3.83 3.81c.19.2.45.3.7.3.25 0 .52-.09.7-.3a.996.996 0 0 0 0-1.41v.01zM7 10.7c-2.59 0-4.7-2.11-4.7-4.7 0-2.59 2.11-4.7 4.7-4.7 2.59 0 4.7 2.11 4.7 4.7 0 2.59-2.11 4.7-4.7 4.7z"/></svg>
    </div>

    <img class="avatar mr-2 flex-shrink-0 js-jump-to-suggestion-avatar d-none" alt="" aria-label="Team" src="" width="28" height="28">

    <div class="jump-to-suggestion-name js-jump-to-suggestion-name flex-auto overflow-hidden text-left no-wrap css-truncate css-truncate-target">
    </div>

    <div class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none js-jump-to-badge-search">
      <span class="js-jump-to-badge-search-text-default d-none" aria-label="in this repository">
        In this repository
      </span>
      <span class="js-jump-to-badge-search-text-global d-none" aria-label="in all of GitHub">
        All GitHub
      </span>
      <span aria-hidden="true" class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>

    <div aria-hidden="true" class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none d-on-nav-focus js-jump-to-badge-jump">
      Jump to
      <span class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>
  </a>
</li>


</ul>

            </div>
      </label>
</form>  </div>
</div>

          </div>

        <a href="/login?return_to=%2Fcoleifer%2Fpeewee%2Fblob%2Fmaster%2Fdocs%2Fpeewee%2Fquery_examples.rst"
          class="HeaderMenu-link no-underline mr-3"
          data-hydro-click="{&quot;event_type&quot;:&quot;authentication.click&quot;,&quot;payload&quot;:{&quot;location_in_page&quot;:&quot;site header menu&quot;,&quot;repository_id&quot;:null,&quot;auth_type&quot;:&quot;SIGN_UP&quot;,&quot;client_id&quot;:null,&quot;originating_request_id&quot;:&quot;D335:7880:6505C:D307D:5D8D3894&quot;,&quot;originating_url&quot;:&quot;https://github.com/coleifer/peewee/blob/master/docs/peewee/query_examples.rst&quot;,&quot;referrer&quot;:null,&quot;user_id&quot;:null}}" data-hydro-click-hmac="ea8b429dfb5d947109e3e0e2b6ed6316d53622b2c8bcf7ca5ef57df45b70db76"
          data-ga-click="(Logged out) Header, clicked Sign in, text:sign-in">
          Sign&nbsp;in
        </a>
          <a href="/join?source=header-repo"
            class="HeaderMenu-link d-inline-block no-underline border border-gray-dark rounded-1 px-2 py-1"
            data-hydro-click="{&quot;event_type&quot;:&quot;authentication.click&quot;,&quot;payload&quot;:{&quot;location_in_page&quot;:&quot;site header menu&quot;,&quot;repository_id&quot;:null,&quot;auth_type&quot;:&quot;SIGN_UP&quot;,&quot;client_id&quot;:null,&quot;originating_request_id&quot;:&quot;D335:7880:6505C:D307D:5D8D3894&quot;,&quot;originating_url&quot;:&quot;https://github.com/coleifer/peewee/blob/master/docs/peewee/query_examples.rst&quot;,&quot;referrer&quot;:null,&quot;user_id&quot;:null}}" data-hydro-click-hmac="ea8b429dfb5d947109e3e0e2b6ed6316d53622b2c8bcf7ca5ef57df45b70db76"
            data-ga-click="(Logged out) Header, clicked Sign up, text:sign-up">
            Sign&nbsp;up
          </a>
      </div>
    </div>
  </div>
</header>

  </div>

  <div id="start-of-content" class="show-on-focus"></div>


    <div id="js-flash-container">

</div>



  <div class="application-main " data-commit-hovercards-enabled>
        <div itemscope itemtype="http://schema.org/SoftwareSourceCode" class="">
    <main  >
      


  










  <div class="pagehead repohead instapaper_ignore readability-menu experiment-repo-nav pt-0 pt-lg-4 ">
    <div class="repohead-details-container clearfix container-lg p-responsive d-none d-lg-block">

      <ul class="pagehead-actions">




  <li>
    
  <a class="tooltipped tooltipped-s btn btn-sm btn-with-count" aria-label="You must be signed in to watch a repository" rel="nofollow" data-hydro-click="{&quot;event_type&quot;:&quot;authentication.click&quot;,&quot;payload&quot;:{&quot;location_in_page&quot;:&quot;notification subscription menu watch&quot;,&quot;repository_id&quot;:null,&quot;auth_type&quot;:&quot;LOG_IN&quot;,&quot;client_id&quot;:null,&quot;originating_request_id&quot;:&quot;D335:7880:6505C:D307D:5D8D3894&quot;,&quot;originating_url&quot;:&quot;https://github.com/coleifer/peewee/blob/master/docs/peewee/query_examples.rst&quot;,&quot;referrer&quot;:null,&quot;user_id&quot;:null}}" data-hydro-click-hmac="d14d87fb895a0008fee7475497ae43f4318730a048c93fdac155074592714aa9" href="/login?return_to=%2Fcoleifer%2Fpeewee">
    <svg class="octicon octicon-eye v-align-text-bottom" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
    Watch
</a>    <a class="social-count" href="/coleifer/peewee/watchers"
       aria-label="198 users are watching this repository">
      198
    </a>

  </li>

  <li>
        <a class="btn btn-sm btn-with-count tooltipped tooltipped-s" aria-label="You must be signed in to star a repository" rel="nofollow" data-hydro-click="{&quot;event_type&quot;:&quot;authentication.click&quot;,&quot;payload&quot;:{&quot;location_in_page&quot;:&quot;star button&quot;,&quot;repository_id&quot;:979480,&quot;auth_type&quot;:&quot;LOG_IN&quot;,&quot;client_id&quot;:null,&quot;originating_request_id&quot;:&quot;D335:7880:6505C:D307D:5D8D3894&quot;,&quot;originating_url&quot;:&quot;https://github.com/coleifer/peewee/blob/master/docs/peewee/query_examples.rst&quot;,&quot;referrer&quot;:null,&quot;user_id&quot;:null}}" data-hydro-click-hmac="27f50c004fd0ebbde49143e16cc325dfc5ddbf101afe1bfb42002f2a6de03d46" href="/login?return_to=%2Fcoleifer%2Fpeewee">
      <svg class="octicon octicon-star v-align-text-bottom" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M14 6l-4.9-.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14 7 11.67 11.33 14l-.93-4.74L14 6z"/></svg>
      Star
</a>
    <a class="social-count js-social-count" href="/coleifer/peewee/stargazers"
      aria-label="6863 users starred this repository">
      6,863
    </a>

  </li>

  <li>
      <a class="btn btn-sm btn-with-count tooltipped tooltipped-s" aria-label="You must be signed in to fork a repository" rel="nofollow" data-hydro-click="{&quot;event_type&quot;:&quot;authentication.click&quot;,&quot;payload&quot;:{&quot;location_in_page&quot;:&quot;repo details fork button&quot;,&quot;repository_id&quot;:979480,&quot;auth_type&quot;:&quot;LOG_IN&quot;,&quot;client_id&quot;:null,&quot;originating_request_id&quot;:&quot;D335:7880:6505C:D307D:5D8D3894&quot;,&quot;originating_url&quot;:&quot;https://github.com/coleifer/peewee/blob/master/docs/peewee/query_examples.rst&quot;,&quot;referrer&quot;:null,&quot;user_id&quot;:null}}" data-hydro-click-hmac="f5c649afe8f0bbcd27e4ab7e0bc1fe023326f791f70da589f5d0bc170cb58cbd" href="/login?return_to=%2Fcoleifer%2Fpeewee">
        <svg class="octicon octicon-repo-forked v-align-text-bottom" viewBox="0 0 10 16" version="1.1" width="10" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8 1a1.993 1.993 0 0 0-1 3.72V6L5 8 3 6V4.72A1.993 1.993 0 0 0 2 1a1.993 1.993 0 0 0-1 3.72V6.5l3 3v1.78A1.993 1.993 0 0 0 5 15a1.993 1.993 0 0 0 1-3.72V9.5l3-3V4.72A1.993 1.993 0 0 0 8 1zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3 10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3-10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"/></svg>
        Fork
</a>
    <a href="/coleifer/peewee/network/members" class="social-count"
       aria-label="1122 users forked this repository">
      1,122
    </a>
  </li>
</ul>

      <h1 class="public ">
    <svg class="octicon octicon-repo" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
  <span class="author" itemprop="author"><a class="url fn" rel="author" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=119974" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/coleifer">coleifer</a></span><!--
--><span class="path-divider">/</span><!--
--><strong itemprop="name"><a data-pjax="#js-repo-pjax-container" href="/coleifer/peewee">peewee</a></strong>
  

</h1>

    </div>
    
<nav class="hx_reponav reponav js-repo-nav js-sidenav-container-pjax container-lg p-responsive d-none d-lg-block"
     itemscope
     itemtype="http://schema.org/BreadcrumbList"
    aria-label="Repository"
     data-pjax="#js-repo-pjax-container">

  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a class="js-selected-navigation-item selected reponav-item" itemprop="url" data-hotkey="g c" aria-current="page" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches repo_packages /coleifer/peewee" href="/coleifer/peewee">
      <svg class="octicon octicon-code" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M9.5 3L8 4.5 11.5 8 8 11.5 9.5 13 14 8 9.5 3zm-5 0L0 8l4.5 5L6 11.5 2.5 8 6 4.5 4.5 3z"/></svg>
      <span itemprop="name">Code</span>
      <meta itemprop="position" content="1">
</a>  </span>

    <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
      <a itemprop="url" data-hotkey="g i" class="js-selected-navigation-item reponav-item" data-selected-links="repo_issues repo_labels repo_milestones /coleifer/peewee/issues" href="/coleifer/peewee/issues">
        <svg class="octicon octicon-issue-opened" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7 2.3c3.14 0 5.7 2.56 5.7 5.7s-2.56 5.7-5.7 5.7A5.71 5.71 0 0 1 1.3 8c0-3.14 2.56-5.7 5.7-5.7zM7 1C3.14 1 0 4.14 0 8s3.14 7 7 7 7-3.14 7-7-3.14-7-7-7zm1 3H6v5h2V4zm0 6H6v2h2v-2z"/></svg>
        <span itemprop="name">Issues</span>
        <span class="Counter">0</span>
        <meta itemprop="position" content="2">
</a>    </span>

  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a data-hotkey="g p" itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="repo_pulls checks /coleifer/peewee/pulls" href="/coleifer/peewee/pulls">
      <svg class="octicon octicon-git-pull-request" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M11 11.28V5c-.03-.78-.34-1.47-.94-2.06C9.46 2.35 8.78 2.03 8 2H7V0L4 3l3 3V4h1c.27.02.48.11.69.31.21.2.3.42.31.69v6.28A1.993 1.993 0 0 0 10 15a1.993 1.993 0 0 0 1-3.72zm-1 2.92c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zM4 3c0-1.11-.89-2-2-2a1.993 1.993 0 0 0-1 3.72v6.56A1.993 1.993 0 0 0 2 15a1.993 1.993 0 0 0 1-3.72V4.72c.59-.34 1-.98 1-1.72zm-.8 10c0 .66-.55 1.2-1.2 1.2-.65 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"/></svg>
      <span itemprop="name">Pull requests</span>
      <span class="Counter">0</span>
      <meta itemprop="position" content="3">
</a>  </span>


    <a data-hotkey="g b" class="js-selected-navigation-item reponav-item" data-selected-links="repo_projects new_repo_project repo_project /coleifer/peewee/projects" href="/coleifer/peewee/projects">
      <svg class="octicon octicon-project" viewBox="0 0 15 16" version="1.1" width="15" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M10 12h3V2h-3v10zm-4-2h3V2H6v8zm-4 4h3V2H2v12zm-1 1h13V1H1v14zM14 0H1a1 1 0 0 0-1 1v14a1 1 0 0 0 1 1h13a1 1 0 0 0 1-1V1a1 1 0 0 0-1-1z"/></svg>
      Projects
      <span class="Counter" >0</span>
</a>

    <a class="js-selected-navigation-item reponav-item" data-hotkey="g w" data-selected-links="repo_wiki /coleifer/peewee/wiki" href="/coleifer/peewee/wiki">
      <svg class="octicon octicon-book" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M3 5h4v1H3V5zm0 3h4V7H3v1zm0 2h4V9H3v1zm11-5h-4v1h4V5zm0 2h-4v1h4V7zm0 2h-4v1h4V9zm2-6v9c0 .55-.45 1-1 1H9.5l-1 1-1-1H2c-.55 0-1-.45-1-1V3c0-.55.45-1 1-1h5.5l1 1 1-1H15c.55 0 1 .45 1 1zm-8 .5L7.5 3H2v9h6V3.5zm7-.5H9.5l-.5.5V12h6V3z"/></svg>
      Wiki
</a>
    <a data-skip-pjax="true" class="js-selected-navigation-item reponav-item" data-selected-links="security alerts policy code_scanning /coleifer/peewee/security/advisories" href="/coleifer/peewee/security/advisories">
      <svg class="octicon octicon-shield" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M0 2l7-2 7 2v6.02C14 12.69 8.69 16 7 16c-1.69 0-7-3.31-7-7.98V2zm1 .75L7 1l6 1.75v5.268C13 12.104 8.449 15 7 15c-1.449 0-6-2.896-6-6.982V2.75zm1 .75L7 2v12c-1.207 0-5-2.482-5-5.985V3.5z"/></svg>
      Security
</a>
    <a class="js-selected-navigation-item reponav-item" data-selected-links="repo_graphs repo_contributors dependency_graph pulse people /coleifer/peewee/pulse" href="/coleifer/peewee/pulse">
      <svg class="octicon octicon-graph" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M16 14v1H0V0h1v14h15zM5 13H3V8h2v5zm4 0H7V3h2v10zm4 0h-2V6h2v7z"/></svg>
      Insights
</a>

</nav>

  <div class="reponav-wrapper reponav-small d-lg-none">
  <nav class="reponav js-reponav text-center no-wrap"
       itemscope
       itemtype="http://schema.org/BreadcrumbList">

    <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
      <a class="js-selected-navigation-item selected reponav-item" itemprop="url" aria-current="page" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches repo_packages /coleifer/peewee" href="/coleifer/peewee">
        <span itemprop="name">Code</span>
        <meta itemprop="position" content="1">
</a>    </span>

      <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
        <a itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="repo_issues repo_labels repo_milestones /coleifer/peewee/issues" href="/coleifer/peewee/issues">
          <span itemprop="name">Issues</span>
          <span class="Counter">0</span>
          <meta itemprop="position" content="2">
</a>      </span>

    <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
      <a itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="repo_pulls checks /coleifer/peewee/pulls" href="/coleifer/peewee/pulls">
        <span itemprop="name">Pull requests</span>
        <span class="Counter">0</span>
        <meta itemprop="position" content="3">
</a>    </span>

      <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
        <a itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="repo_projects new_repo_project repo_project /coleifer/peewee/projects" href="/coleifer/peewee/projects">
          <span itemprop="name">Projects</span>
          <span class="Counter">0</span>
          <meta itemprop="position" content="4">
</a>      </span>

      <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
        <a itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="repo_wiki /coleifer/peewee/wiki" href="/coleifer/peewee/wiki">
          <span itemprop="name">Wiki</span>
          <meta itemprop="position" content="5">
</a>      </span>

      <a itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="security alerts policy code_scanning /coleifer/peewee/security/advisories" href="/coleifer/peewee/security/advisories">
        <span itemprop="name">Security</span>
        <meta itemprop="position" content="6">
</a>
      <a class="js-selected-navigation-item reponav-item" data-selected-links="pulse /coleifer/peewee/pulse" href="/coleifer/peewee/pulse">
        Pulse
</a>

  </nav>
</div>


  </div>
<div class="container-lg clearfix new-discussion-timeline experiment-repo-nav  p-responsive">
  <div class="repository-content ">

    
    


  


    <a class="d-none js-permalink-shortcut" data-hotkey="y" href="/coleifer/peewee/blob/254e9b58e7193218c4fd35e8282c08cdb3063299/docs/peewee/query_examples.rst">Permalink</a>

    <!-- blob contrib key: blob_contributors:v21:dbedc1f87d696c6c47ca73ebfd6e4532 -->
          <div class="signup-prompt-bg rounded-1">
      <div class="signup-prompt p-4 text-center mb-4 rounded-1">
        <div class="position-relative">
          <!-- '"` --><!-- </textarea></xmp> --></option></form><form action="/prompt_dismissals/signup" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="_method" value="put" /><input type="hidden" name="authenticity_token" value="4sfruNnrEPjhw0K6pCAtT7+KE/M8HlrbEFOn6cqulVwS/mKJLbvNddscY7vd8dTsyTbIH7I3VyWkqKirYFWchQ==" />
            <button type="submit" class="position-absolute top-0 right-0 btn-link link-gray" data-ga-click="(Logged out) Sign up prompt, clicked Dismiss, text:dismiss">
              Dismiss
            </button>
</form>          <h3 class="pt-2">Join GitHub today</h3>
          <p class="col-6 mx-auto">GitHub is home to over 40 million developers working together to host and review code, manage projects, and build software together.</p>
          <a class="btn btn-primary" data-hydro-click="{&quot;event_type&quot;:&quot;authentication.click&quot;,&quot;payload&quot;:{&quot;location_in_page&quot;:&quot;files signup prompt&quot;,&quot;repository_id&quot;:null,&quot;auth_type&quot;:&quot;SIGN_UP&quot;,&quot;client_id&quot;:null,&quot;originating_request_id&quot;:&quot;D335:7880:6505C:D307D:5D8D3894&quot;,&quot;originating_url&quot;:&quot;https://github.com/coleifer/peewee/blob/master/docs/peewee/query_examples.rst&quot;,&quot;referrer&quot;:null,&quot;user_id&quot;:null}}" data-hydro-click-hmac="05a12c260b16f2c758e5b0888b2323beae543614e5bb185c899a4110dd1ebb84" data-ga-click="(Logged out) Sign up prompt, clicked Sign up, text:sign-up" href="/join?source=prompt-blob-show">Sign up</a>
        </div>
      </div>
    </div>


    <div class="d-flex flex-items-start flex-shrink-0 pb-3 flex-column flex-md-row">
      <span class="d-flex flex-justify-between width-full width-md-auto">
        
<details class="details-reset details-overlay select-menu branch-select-menu  hx_rsm" id="branch-select-menu">
  <summary class="btn btn-sm select-menu-button css-truncate"
           data-hotkey="w"
           title="Switch branches or tags">
    <i>Branch:</i>
    <span class="css-truncate-target" data-menu-button>master</span>
  </summary>

  <details-menu class="select-menu-modal hx_rsm-modal position-absolute" style="z-index: 99;" src="/coleifer/peewee/ref-list/master/docs/peewee/query_examples.rst?source_action=show&amp;source_controller=blob" preload>
    <include-fragment class="select-menu-loading-overlay anim-pulse">
      <svg height="32" class="octicon octicon-octoface" viewBox="0 0 16 16" version="1.1" width="32" aria-hidden="true"><path fill-rule="evenodd" d="M14.7 5.34c.13-.32.55-1.59-.13-3.31 0 0-1.05-.33-3.44 1.3-1-.28-2.07-.32-3.13-.32s-2.13.04-3.13.32c-2.39-1.64-3.44-1.3-3.44-1.3-.68 1.72-.26 2.99-.13 3.31C.49 6.21 0 7.33 0 8.69 0 13.84 3.33 15 7.98 15S16 13.84 16 8.69c0-1.36-.49-2.48-1.3-3.35zM8 14.02c-3.3 0-5.98-.15-5.98-3.35 0-.76.38-1.48 1.02-2.07 1.07-.98 2.9-.46 4.96-.46 2.07 0 3.88-.52 4.96.46.65.59 1.02 1.3 1.02 2.07 0 3.19-2.68 3.35-5.98 3.35zM5.49 9.01c-.66 0-1.2.8-1.2 1.78s.54 1.79 1.2 1.79c.66 0 1.2-.8 1.2-1.79s-.54-1.78-1.2-1.78zm5.02 0c-.66 0-1.2.79-1.2 1.78s.54 1.79 1.2 1.79c.66 0 1.2-.8 1.2-1.79s-.53-1.78-1.2-1.78z"/></svg>
    </include-fragment>
  </details-menu>
</details>

        <div class="BtnGroup flex-shrink-0 d-md-none">
          <a href="/coleifer/peewee/find/master"
                class="js-pjax-capture-input btn btn-sm BtnGroup-item"
                data-pjax
                data-hotkey="t">
            Find file
          </a>
          <clipboard-copy value="docs/peewee/query_examples.rst" class="btn btn-sm BtnGroup-item">
            Copy path
          </clipboard-copy>
        </div>
      </span>
      <h2 id="blob-path" class="breadcrumb flex-auto min-width-0 text-normal flex-md-self-center ml-md-2 mr-md-3 my-2 my-md-0">
        <span class="js-repo-root text-bold"><span class="js-path-segment"><a data-pjax="true" href="/coleifer/peewee"><span>peewee</span></a></span></span><span class="separator">/</span><span class="js-path-segment"><a data-pjax="true" href="/coleifer/peewee/tree/master/docs"><span>docs</span></a></span><span class="separator">/</span><span class="js-path-segment"><a data-pjax="true" href="/coleifer/peewee/tree/master/docs/peewee"><span>peewee</span></a></span><span class="separator">/</span><strong class="final-path">query_examples.rst</strong>
      </h2>

      <div class="BtnGroup flex-shrink-0 d-none d-md-inline-block">
        <a href="/coleifer/peewee/find/master"
              class="js-pjax-capture-input btn btn-sm BtnGroup-item"
              data-pjax
              data-hotkey="t">
          Find file
        </a>
        <clipboard-copy value="docs/peewee/query_examples.rst" class="btn btn-sm BtnGroup-item">
          Copy path
        </clipboard-copy>
      </div>
    </div>



    
  <div class="Box Box--condensed d-flex flex-column flex-shrink-0">
      <div class="Box-body d-flex flex-justify-between bg-blue-light flex-column flex-md-row flex-items-start flex-md-items-center">
        <span class="pr-md-4 f6">
          <a rel="author" data-skip-pjax="true" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=119974" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/coleifer"><img class="avatar" src="https://avatars1.githubusercontent.com/u/119974?s=40&amp;v=4" width="20" height="20" alt="@coleifer" /></a>
          <a class="text-bold link-gray-dark lh-default v-align-middle" rel="author" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=119974" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/coleifer">coleifer</a>
            <span class="lh-default v-align-middle">
              <a data-pjax="true" title="Include call to .execute() in query examples." class="link-gray" href="/coleifer/peewee/commit/d67890db547e221a8dce07b67299ee0efdf7e420">Include call to .execute() in query examples.</a>
            </span>
        </span>
        <span class="d-inline-block flex-shrink-0 v-align-bottom f6 mt-2 mt-md-0">
          <a class="pr-2 text-mono link-gray" href="/coleifer/peewee/commit/d67890db547e221a8dce07b67299ee0efdf7e420" data-pjax>d67890d</a>
          <relative-time datetime="2018-07-26T21:13:46Z">Jul 26, 2018</relative-time>
        </span>
      </div>

    <div class="Box-body d-flex flex-items-center flex-auto f6 border-bottom-0 flex-wrap" >
      <details class="details-reset details-overlay details-overlay-dark lh-default text-gray-dark float-left mr-2" id="blob_contributors_box">
        <summary class="btn-link">
          <span><strong>1</strong> contributor</span>
        </summary>
        <details-dialog
          class="Box Box--overlay d-flex flex-column anim-fade-in fast"
          aria-label="Users who have contributed to this file"
          src="/coleifer/peewee/contributors/master/docs/peewee/query_examples.rst/list" preload>
          <div class="Box-header">
            <button class="Box-btn-octicon btn-octicon float-right" type="button" aria-label="Close dialog" data-close-dialog>
              <svg class="octicon octicon-x" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"/></svg>
            </button>
            <h3 class="Box-title">
              Users who have contributed to this file
            </h3>
          </div>
          <include-fragment class="octocat-spinner my-3" aria-label="Loading..."></include-fragment>
        </details-dialog>
      </details>
    </div>
  </div>





    <div class="Box mt-3 position-relative">
      
<div class="Box-header py-2 d-flex flex-column flex-shrink-0 flex-md-row flex-md-items-center">

  <div class="text-mono f6 flex-auto pr-3 flex-order-2 flex-md-order-1 mt-2 mt-md-0">
      1389 lines (979 sloc)
      <span class="file-info-divider"></span>
    42.7 KB
  </div>

  <div class="d-flex py-1 py-md-0 flex-auto flex-order-1 flex-md-order-2 flex-sm-grow-0 flex-justify-between">

    <div class="BtnGroup">
      <a id="raw-url" class="btn btn-sm BtnGroup-item" href="/coleifer/peewee/raw/master/docs/peewee/query_examples.rst">Raw</a>
        <a class="btn btn-sm js-update-url-with-hash BtnGroup-item" data-hotkey="b" href="/coleifer/peewee/blame/master/docs/peewee/query_examples.rst">Blame</a>
      <a rel="nofollow" class="btn btn-sm BtnGroup-item" href="/coleifer/peewee/commits/master/docs/peewee/query_examples.rst">History</a>
    </div>


    <div>

          <button type="button" class="btn-octicon disabled tooltipped tooltipped-nw"
            aria-label="You must be signed in to make or propose changes">
            <svg class="octicon octicon-pencil" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M0 12v3h3l8-8-3-3-8 8zm3 2H1v-2h1v1h1v1zm10.3-9.3L12 6 9 3l1.3-1.3a.996.996 0 0 1 1.41 0l1.59 1.59c.39.39.39 1.02 0 1.41z"/></svg>
          </button>
          <button type="button" class="btn-octicon btn-octicon-danger disabled tooltipped tooltipped-nw"
            aria-label="You must be signed in to make or propose changes">
            <svg class="octicon octicon-trashcan" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M11 2H9c0-.55-.45-1-1-1H5c-.55 0-1 .45-1 1H2c-.55 0-1 .45-1 1v1c0 .55.45 1 1 1v9c0 .55.45 1 1 1h7c.55 0 1-.45 1-1V5c.55 0 1-.45 1-1V3c0-.55-.45-1-1-1zm-1 12H3V5h1v8h1V5h1v8h1V5h1v8h1V5h1v9zm1-10H2V3h9v1z"/></svg>
          </button>
    </div>
  </div>
</div>




      
  <div id="readme" class="Box-body readme blob instapaper_body js-code-block-container">
    <article class="markdown-body entry-content p-3 p-md-6" itemprop="text"><h1><a id="user-content-query-examples" class="anchor" aria-hidden="true" href="#query-examples"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Query Examples</h1>
<p>These query examples are taken from the site <a href="https://pgexercises.com/" rel="nofollow">PostgreSQL Exercises</a>. A sample data-set can be found on the <a href="https://pgexercises.com/gettingstarted.html" rel="nofollow">getting
started page</a>.</p>
<p>Here is a visual representation of the schema used in these examples:</p>
<p><a target="_blank" rel="noopener noreferrer" href="/coleifer/peewee/blob/master/docs/peewee/schema-horizontal.png"><img alt="schema-horizontal.png" src="/coleifer/peewee/raw/master/docs/peewee/schema-horizontal.png" style="max-width:100%;"></a></p>
<a name="user-content-model-definitions"></a>
<h2><a id="user-content-model-definitions" class="anchor" aria-hidden="true" href="#model-definitions"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Model Definitions</h2>
<p>To begin working with the data, we'll define the model classes that correspond
to the tables in the diagram.</p>
<div>
<p>Note</p>
<p>In some cases we explicitly specify column names for a particular field.
This is so our models are compatible with the database schema used for the
postgres exercises.</p>
</div>
<div class="highlight highlight-source-python"><pre><span class="pl-k">from</span> functools <span class="pl-k">import</span> partial
<span class="pl-k">from</span> peewee <span class="pl-k">import</span> <span class="pl-k">*</span>


db <span class="pl-k">=</span> PostgresqlDatabase(<span class="pl-s"><span class="pl-pds">'</span>peewee_test<span class="pl-pds">'</span></span>)

<span class="pl-k">class</span> <span class="pl-en">BaseModel</span>(<span class="pl-e">Model</span>):
    <span class="pl-k">class</span> <span class="pl-en">Meta</span>:
        database <span class="pl-k">=</span> db

<span class="pl-k">class</span> <span class="pl-en">Member</span>(<span class="pl-e">BaseModel</span>):
    memid <span class="pl-k">=</span> AutoField()  <span class="pl-c"><span class="pl-c">#</span> Auto-incrementing primary key.</span>
    surname <span class="pl-k">=</span> CharField()
    firstname <span class="pl-k">=</span> CharField()
    address <span class="pl-k">=</span> CharField(<span class="pl-v">max_length</span><span class="pl-k">=</span><span class="pl-c1">300</span>)
    zipcode <span class="pl-k">=</span> IntegerField()
    telephone <span class="pl-k">=</span> CharField()
    recommendedby <span class="pl-k">=</span> ForeignKeyField(<span class="pl-s"><span class="pl-pds">'</span>self<span class="pl-pds">'</span></span>, <span class="pl-v">backref</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">'</span>recommended<span class="pl-pds">'</span></span>,
                                    <span class="pl-v">column_name</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">'</span>recommendedby<span class="pl-pds">'</span></span>, <span class="pl-v">null</span><span class="pl-k">=</span><span class="pl-c1">True</span>)
    joindate <span class="pl-k">=</span> DateTimeField()

    <span class="pl-k">class</span> <span class="pl-en">Meta</span>:
        table_name <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">'</span>members<span class="pl-pds">'</span></span>


<span class="pl-c"><span class="pl-c">#</span> Conveniently declare decimal fields suitable for storing currency.</span>
MoneyField <span class="pl-k">=</span> partial(DecimalField, <span class="pl-v">decimal_places</span><span class="pl-k">=</span><span class="pl-c1">2</span>)


<span class="pl-k">class</span> <span class="pl-en">Facility</span>(<span class="pl-e">BaseModel</span>):
    facid <span class="pl-k">=</span> AutoField()
    name <span class="pl-k">=</span> CharField()
    membercost <span class="pl-k">=</span> MoneyField()
    guestcost <span class="pl-k">=</span> MoneyField()
    initialoutlay <span class="pl-k">=</span> MoneyField()
    monthlymaintenance <span class="pl-k">=</span> MoneyField()

    <span class="pl-k">class</span> <span class="pl-en">Meta</span>:
        table_name <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">'</span>facilities<span class="pl-pds">'</span></span>


<span class="pl-k">class</span> <span class="pl-en">Booking</span>(<span class="pl-e">BaseModel</span>):
    bookid <span class="pl-k">=</span> AutoField()
    facility <span class="pl-k">=</span> ForeignKeyField(Facility, <span class="pl-v">column_name</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">'</span>facid<span class="pl-pds">'</span></span>)
    member <span class="pl-k">=</span> ForeignKeyField(Member, <span class="pl-v">column_name</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">'</span>memid<span class="pl-pds">'</span></span>)
    starttime <span class="pl-k">=</span> DateTimeField()
    slots <span class="pl-k">=</span> IntegerField()

    <span class="pl-k">class</span> <span class="pl-en">Meta</span>:
        table_name <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">'</span>bookings<span class="pl-pds">'</span></span></pre></div>
<a name="user-content-schema-creation"></a>
<h2><a id="user-content-schema-creation" class="anchor" aria-hidden="true" href="#schema-creation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Schema Creation</h2>
<p>If you downloaded the SQL file from the PostgreSQL Exercises site, then you can
load the data into a PostgreSQL database using the following commands:</p>
<pre>createdb peewee_test
psql -U postgres -f clubdata.sql -d peewee_test -x -q
</pre>
<p>To create the schema using Peewee, without loading the sample data, you can run
the following:</p>
<div class="highlight highlight-source-python"><pre><span class="pl-c"><span class="pl-c">#</span> Assumes you have created the database "peewee_test" already.</span>
db.create_tables([Member, Facility, Booking])</pre></div>
<a name="user-content-basic-exercises"></a>
<h2><a id="user-content-basic-exercises" class="anchor" aria-hidden="true" href="#basic-exercises"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Basic Exercises</h2>
<p>This category deals with the basics of SQL. It covers select and where clauses,
case expressions, unions, and a few other odds and ends.</p>
<a name="user-content-retrieve-everything"></a>
<h3><a id="user-content-retrieve-everything" class="anchor" aria-hidden="true" href="#retrieve-everything"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Retrieve everything</h3>
<p>Retrieve all information from facilities table.</p>
<div class="highlight highlight-source-sql"><pre><span class="pl-k">SELECT</span> <span class="pl-k">*</span> <span class="pl-k">FROM</span> facilities</pre></div>
<div class="highlight highlight-source-python"><pre><span class="pl-c"><span class="pl-c">#</span> By default, when no fields are explicitly passed to select(), all fields</span>
<span class="pl-c"><span class="pl-c">#</span> will be selected.</span>
query <span class="pl-k">=</span> Facility.select()</pre></div>
<a name="user-content-retrieve-specific-columns-from-a-table"></a>
<h3><a id="user-content-retrieve-specific-columns-from-a-table" class="anchor" aria-hidden="true" href="#retrieve-specific-columns-from-a-table"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Retrieve specific columns from a table</h3>
<p>Retrieve names of facilities and cost to members.</p>
<div class="highlight highlight-source-sql"><pre><span class="pl-k">SELECT</span> name, membercost <span class="pl-k">FROM</span> facilities;</pre></div>
<div class="highlight highlight-source-python"><pre>query <span class="pl-k">=</span> Facility.select(Facility.name, Facility.membercost)

<span class="pl-c"><span class="pl-c">#</span> To iterate:</span>
<span class="pl-k">for</span> facility <span class="pl-k">in</span> query:
    <span class="pl-c1">print</span>(facility.name)</pre></div>
<a name="user-content-control-which-rows-are-retrieved"></a>
<h3><a id="user-content-control-which-rows-are-retrieved" class="anchor" aria-hidden="true" href="#control-which-rows-are-retrieved"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Control which rows are retrieved</h3>
<p>Retrieve list of facilities that have a cost to members.</p>
<div class="highlight highlight-source-sql"><pre><span class="pl-k">SELECT</span> <span class="pl-k">*</span> <span class="pl-k">FROM</span> facilities <span class="pl-k">WHERE</span> membercost <span class="pl-k">&gt;</span> <span class="pl-c1">0</span></pre></div>
<div class="highlight highlight-source-python"><pre>query <span class="pl-k">=</span> Facility.select().where(Facility.membercost <span class="pl-k">&gt;</span> <span class="pl-c1">0</span>)</pre></div>
<a name="user-content-control-which-rows-are-retrieved-part-2"></a>
<h3><a id="user-content-control-which-rows-are-retrieved---part-2" class="anchor" aria-hidden="true" href="#control-which-rows-are-retrieved---part-2"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Control which rows are retrieved - part 2</h3>
<p>Retrieve list of facilities that have a cost to members, and that fee is less
than 1/50th of the monthly maintenance cost. Return id, name, cost and
monthly-maintenance.</p>
<div class="highlight highlight-source-sql"><pre><span class="pl-k">SELECT</span> facid, name, membercost, monthlymaintenance
<span class="pl-k">FROM</span> facilities
<span class="pl-k">WHERE</span> membercost <span class="pl-k">&gt;</span> <span class="pl-c1">0</span> <span class="pl-k">AND</span> membercost <span class="pl-k">&lt;</span> (monthlymaintenance <span class="pl-k">/</span> <span class="pl-c1">50</span>)</pre></div>
<div class="highlight highlight-source-python"><pre>query <span class="pl-k">=</span> (Facility
         .select(Facility.facid, Facility.name, Facility.membercost,
                 Facility.monthlymaintenance)
         .where(
             (Facility.membercost <span class="pl-k">&gt;</span> <span class="pl-c1">0</span>) <span class="pl-k">&amp;</span>
             (Facility.membercost <span class="pl-k">&lt;</span> (Facility.monthlymaintenance <span class="pl-k">/</span> <span class="pl-c1">50</span>))))</pre></div>
<a name="user-content-basic-string-searches"></a>
<h3><a id="user-content-basic-string-searches" class="anchor" aria-hidden="true" href="#basic-string-searches"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Basic string searches</h3>
<p>How can you produce a list of all facilities with the word 'Tennis' in their
name?</p>
<div class="highlight highlight-source-sql"><pre><span class="pl-k">SELECT</span> <span class="pl-k">*</span> <span class="pl-k">FROM</span> facilities <span class="pl-k">WHERE</span> name ILIKE <span class="pl-s"><span class="pl-pds">'</span>%tennis%<span class="pl-pds">'</span></span>;</pre></div>
<div class="highlight highlight-source-python"><pre>query <span class="pl-k">=</span> Facility.select().where(Facility.name.contains(<span class="pl-s"><span class="pl-pds">'</span>tennis<span class="pl-pds">'</span></span>))

<span class="pl-c"><span class="pl-c">#</span> OR use the exponent operator. Note: you must include wildcards here:</span>
query <span class="pl-k">=</span> Facility.select().where(Facility.name <span class="pl-k">**</span> <span class="pl-s"><span class="pl-pds">'</span>%tennis%<span class="pl-pds">'</span></span>)</pre></div>
<a name="user-content-matching-against-multiple-possible-values"></a>
<h3><a id="user-content-matching-against-multiple-possible-values" class="anchor" aria-hidden="true" href="#matching-against-multiple-possible-values"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Matching against multiple possible values</h3>
<p>How can you retrieve the details of facilities with ID 1 and 5? Try to do it
without using the OR operator.</p>
<div class="highlight highlight-source-sql"><pre><span class="pl-k">SELECT</span> <span class="pl-k">*</span> <span class="pl-k">FROM</span> facilities <span class="pl-k">WHERE</span> facid <span class="pl-k">IN</span> (<span class="pl-c1">1</span>, <span class="pl-c1">5</span>);</pre></div>
<div class="highlight highlight-source-python"><pre>query <span class="pl-k">=</span> Facility.select().where(Facility.facid.in_([<span class="pl-c1">1</span>, <span class="pl-c1">5</span>]))

<span class="pl-c"><span class="pl-c">#</span> OR:</span>
query <span class="pl-k">=</span> Facility.select().where((Facility.facid <span class="pl-k">==</span> <span class="pl-c1">1</span>) <span class="pl-k">|</span>
                                (Facility.facid <span class="pl-k">==</span> <span class="pl-c1">5</span>))</pre></div>
<a name="user-content-classify-results-into-buckets"></a>
<h3><a id="user-content-classify-results-into-buckets" class="anchor" aria-hidden="true" href="#classify-results-into-buckets"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Classify results into buckets</h3>
<p>How can you produce a list of facilities, with each labelled as 'cheap' or
'expensive' depending on if their monthly maintenance cost is more than $100?
Return the name and monthly maintenance of the facilities in question.</p>
<div class="highlight highlight-source-sql"><pre><span class="pl-k">SELECT</span> name,
CASE WHEN monthlymaintenance <span class="pl-k">&gt;</span> <span class="pl-c1">100</span> THEN <span class="pl-s"><span class="pl-pds">'</span>expensive<span class="pl-pds">'</span></span> ELSE <span class="pl-s"><span class="pl-pds">'</span>cheap<span class="pl-pds">'</span></span> END
<span class="pl-k">FROM</span> facilities;</pre></div>
<div class="highlight highlight-source-python"><pre>cost <span class="pl-k">=</span> Case(<span class="pl-c1">None</span>, [(Facility.monthlymaintenance <span class="pl-k">&gt;</span> <span class="pl-c1">100</span>, <span class="pl-s"><span class="pl-pds">'</span>expensive<span class="pl-pds">'</span></span>)], <span class="pl-s"><span class="pl-pds">'</span>cheap<span class="pl-pds">'</span></span>)
query <span class="pl-k">=</span> Facility.select(Facility.name, cost.alias(<span class="pl-s"><span class="pl-pds">'</span>cost<span class="pl-pds">'</span></span>))</pre></div>
<div>
<p>Note</p>
<p>See documentation <a href="#id2"><span id="user-content-id3">:py:class:`Case`</span></a> for more examples.</p>
</div>
<a name="user-content-working-with-dates"></a>
<h3><a id="user-content-working-with-dates" class="anchor" aria-hidden="true" href="#working-with-dates"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Working with dates</h3>
<p>How can you produce a list of members who joined after the start of September
2012? Return the memid, surname, firstname, and joindate of the members in
question.</p>
<div class="highlight highlight-source-sql"><pre><span class="pl-k">SELECT</span> memid, surname, firstname, joindate <span class="pl-k">FROM</span> members
<span class="pl-k">WHERE</span> joindate <span class="pl-k">&gt;=</span> <span class="pl-s"><span class="pl-pds">'</span>2012-09-01<span class="pl-pds">'</span></span>;</pre></div>
<div class="highlight highlight-source-python"><pre>query <span class="pl-k">=</span> (Member
         .select(Member.memid, Member.surname, Member.firstname, Member.joindate)
         .where(Member.joindate <span class="pl-k">&gt;=</span> datetime.date(<span class="pl-c1">2012</span>, <span class="pl-c1">9</span>, <span class="pl-c1">1</span>)))</pre></div>
<a name="user-content-removing-duplicates-and-ordering-results"></a>
<h3><a id="user-content-removing-duplicates-and-ordering-results" class="anchor" aria-hidden="true" href="#removing-duplicates-and-ordering-results"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Removing duplicates, and ordering results</h3>
<p>How can you produce an ordered list of the first 10 surnames in the members
table? The list must not contain duplicates.</p>
<div class="highlight highlight-source-sql"><pre><span class="pl-k">SELECT DISTINCT</span> surname <span class="pl-k">FROM</span> members <span class="pl-k">ORDER BY</span> surname <span class="pl-k">LIMIT</span> <span class="pl-c1">10</span>;</pre></div>
<div class="highlight highlight-source-python"><pre>query <span class="pl-k">=</span> (Member
         .select(Member.surname)
         .order_by(Member.surname)
         .limit(<span class="pl-c1">10</span>)
         .distinct())</pre></div>
<a name="user-content-combining-results-from-multiple-queries"></a>
<h3><a id="user-content-combining-results-from-multiple-queries" class="anchor" aria-hidden="true" href="#combining-results-from-multiple-queries"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Combining results from multiple queries</h3>
<p>You, for some reason, want a combined list of all surnames and all facility
names.</p>
<div class="highlight highlight-source-sql"><pre><span class="pl-k">SELECT</span> surname <span class="pl-k">FROM</span> members <span class="pl-k">UNION</span> <span class="pl-k">SELECT</span> name <span class="pl-k">FROM</span> facilities;</pre></div>
<div class="highlight highlight-source-python"><pre>lhs <span class="pl-k">=</span> Member.select(Member.surname)
rhs <span class="pl-k">=</span> Facility.select(Facility.name)
query <span class="pl-k">=</span> lhs <span class="pl-k">|</span> rhs</pre></div>
<p>Queries can be composed using the following operators:</p>
<ul>
<li><code>|</code> - <code>UNION</code></li>
<li><code>+</code> - <code>UNION ALL</code></li>
<li><code>&amp;</code> - <code>INTERSECT</code></li>
<li><code>-</code> - <code>EXCEPT</code></li>
</ul>
<a name="user-content-simple-aggregation"></a>
<h3><a id="user-content-simple-aggregation" class="anchor" aria-hidden="true" href="#simple-aggregation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Simple aggregation</h3>
<p>You'd like to get the signup date of your last member. How can you retrieve
this information?</p>
<div class="highlight highlight-source-sql"><pre><span class="pl-k">SELECT</span> <span class="pl-c1">MAX</span>(join_date) <span class="pl-k">FROM</span> members;</pre></div>
<div class="highlight highlight-source-python"><pre>query <span class="pl-k">=</span> Member.select(fn.MAX(Member.joindate))
<span class="pl-c"><span class="pl-c">#</span> To conveniently obtain a single scalar value, use "scalar()":</span>
<span class="pl-c"><span class="pl-c">#</span> max_join_date = query.scalar()</span></pre></div>
<a name="user-content-more-aggregation"></a>
<h3><a id="user-content-more-aggregation" class="anchor" aria-hidden="true" href="#more-aggregation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>More aggregation</h3>
<p>You'd like to get the first and last name of the last member(s) who signed up
- not just the date.</p>
<div class="highlight highlight-source-sql"><pre><span class="pl-k">SELECT</span> firstname, surname, joindate <span class="pl-k">FROM</span> members
<span class="pl-k">WHERE</span> joindate <span class="pl-k">=</span> (<span class="pl-k">SELECT</span> <span class="pl-c1">MAX</span>(joindate) <span class="pl-k">FROM</span> members);</pre></div>
<div class="highlight highlight-source-python"><pre><span class="pl-c"><span class="pl-c">#</span> Use "alias()" to reference the same table multiple times in a query.</span>
MemberAlias <span class="pl-k">=</span> Member.alias()
subq <span class="pl-k">=</span> MemberAlias.select(fn.MAX(MemberAlias.joindate))
query <span class="pl-k">=</span> (Member
         .select(Member.firstname, Member.surname, Member.joindate)
         .where(Member.joindate <span class="pl-k">==</span> subq))</pre></div>
<a name="user-content-joins-and-subqueries"></a>
<h2><a id="user-content-joins-and-subqueries" class="anchor" aria-hidden="true" href="#joins-and-subqueries"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Joins and Subqueries</h2>
<p>This category deals primarily with a foundational concept in relational
database systems: joining. Joining allows you to combine related information
from multiple tables to answer a question. This isn't just beneficial for ease
of querying: a lack of join capability encourages denormalisation of data,
which increases the complexity of keeping your data internally consistent.</p>
<p>This topic covers inner, outer, and self joins, as well as spending a little
time on subqueries (queries within queries).</p>
<a name="user-content-retrieve-the-start-times-of-members-bookings"></a>
<h3><a id="user-content-retrieve-the-start-times-of-members-bookings" class="anchor" aria-hidden="true" href="#retrieve-the-start-times-of-members-bookings"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Retrieve the start times of members' bookings</h3>
<p>How can you produce a list of the start times for bookings by members named
'David Farrell'?</p>
<div class="highlight highlight-source-sql"><pre><span class="pl-k">SELECT</span> starttime <span class="pl-k">FROM</span> bookings
<span class="pl-k">INNER JOIN</span> members <span class="pl-k">ON</span> (<span class="pl-c1">bookings</span>.<span class="pl-c1">memid</span> <span class="pl-k">=</span> <span class="pl-c1">members</span>.<span class="pl-c1">memid</span>)
<span class="pl-k">WHERE</span> surname <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">'</span>Farrell<span class="pl-pds">'</span></span> <span class="pl-k">AND</span> firstname <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">'</span>David<span class="pl-pds">'</span></span>;</pre></div>
<div class="highlight highlight-source-python"><pre>query <span class="pl-k">=</span> (Booking
         .select(Booking.starttime)
         .join(Member)
         .where((Member.surname <span class="pl-k">==</span> <span class="pl-s"><span class="pl-pds">'</span>Farrell<span class="pl-pds">'</span></span>) <span class="pl-k">&amp;</span>
                (Member.firstname <span class="pl-k">==</span> <span class="pl-s"><span class="pl-pds">'</span>David<span class="pl-pds">'</span></span>)))</pre></div>
<a name="user-content-work-out-the-start-times-of-bookings-for-tennis-courts"></a>
<h3><a id="user-content-work-out-the-start-times-of-bookings-for-tennis-courts" class="anchor" aria-hidden="true" href="#work-out-the-start-times-of-bookings-for-tennis-courts"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Work out the start times of bookings for tennis courts</h3>
<p>How can you produce a list of the start times for bookings for tennis courts,
for the date '2012-09-21'? Return a list of start time and facility name
pairings, ordered by the time.</p>
<div class="highlight highlight-source-sql"><pre><span class="pl-k">SELECT</span> starttime, name
<span class="pl-k">FROM</span> bookings
<span class="pl-k">INNER JOIN</span> facilities <span class="pl-k">ON</span> (<span class="pl-c1">bookings</span>.<span class="pl-c1">facid</span> <span class="pl-k">=</span> <span class="pl-c1">facilities</span>.<span class="pl-c1">facid</span>)
<span class="pl-k">WHERE</span> date_trunc(<span class="pl-s"><span class="pl-pds">'</span>day<span class="pl-pds">'</span></span>, starttime) <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">'</span>2012-09-21<span class="pl-pds">'</span></span>:: <span class="pl-k">date</span>
  <span class="pl-k">AND</span> name ILIKE <span class="pl-s"><span class="pl-pds">'</span>tennis%<span class="pl-pds">'</span></span>
<span class="pl-k">ORDER BY</span> starttime, name;</pre></div>
<div class="highlight highlight-source-python"><pre>query <span class="pl-k">=</span> (Booking
         .select(Booking.starttime, Facility.name)
         .join(Facility)
         .where(
             (fn.date_trunc(<span class="pl-s"><span class="pl-pds">'</span>day<span class="pl-pds">'</span></span>, Booking.starttime) <span class="pl-k">==</span> datetime.date(<span class="pl-c1">2012</span>, <span class="pl-c1">9</span>, <span class="pl-c1">21</span>)) <span class="pl-k">&amp;</span>
             Facility.name.startswith(<span class="pl-s"><span class="pl-pds">'</span>Tennis<span class="pl-pds">'</span></span>))
         .order_by(Booking.starttime, Facility.name))

<span class="pl-c"><span class="pl-c">#</span> To retrieve the joined facility's name when iterating:</span>
<span class="pl-k">for</span> booking <span class="pl-k">in</span> query:
    <span class="pl-c1">print</span>(booking.starttime, booking.facility.name)</pre></div>
<a name="user-content-produce-a-list-of-all-members-who-have-recommended-another-member"></a>
<h3><a id="user-content-produce-a-list-of-all-members-who-have-recommended-another-member" class="anchor" aria-hidden="true" href="#produce-a-list-of-all-members-who-have-recommended-another-member"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Produce a list of all members who have recommended another member</h3>
<p>How can you output a list of all members who have recommended another member?
Ensure that there are no duplicates in the list, and that results are ordered
by (surname, firstname).</p>
<div class="highlight highlight-source-sql"><pre><span class="pl-k">SELECT DISTINCT</span> <span class="pl-c1">m</span>.<span class="pl-c1">firstname</span>, <span class="pl-c1">m</span>.<span class="pl-c1">surname</span>
<span class="pl-k">FROM</span> members <span class="pl-k">AS</span> m2
<span class="pl-k">INNER JOIN</span> members <span class="pl-k">AS</span> m <span class="pl-k">ON</span> (<span class="pl-c1">m</span>.<span class="pl-c1">memid</span> <span class="pl-k">=</span> <span class="pl-c1">m2</span>.<span class="pl-c1">recommendedby</span>)
<span class="pl-k">ORDER BY</span> <span class="pl-c1">m</span>.<span class="pl-c1">surname</span>, <span class="pl-c1">m</span>.<span class="pl-c1">firstname</span>;</pre></div>
<div class="highlight highlight-source-python"><pre><span class="pl-c1">MA</span> <span class="pl-k">=</span> Member.alias()
query <span class="pl-k">=</span> (Member
         .select(Member.firstname, Member.surname)
         .join(<span class="pl-c1">MA</span>, <span class="pl-v">on</span><span class="pl-k">=</span>(<span class="pl-c1">MA</span>.recommendedby <span class="pl-k">==</span> Member.memid))
         .order_by(Member.surname, Member.firstname))</pre></div>
<a name="user-content-produce-a-list-of-all-members-along-with-their-recommender"></a>
<h3><a id="user-content-produce-a-list-of-all-members-along-with-their-recommender" class="anchor" aria-hidden="true" href="#produce-a-list-of-all-members-along-with-their-recommender"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Produce a list of all members, along with their recommender</h3>
<p>How can you output a list of all members, including the individual who
recommended them (if any)? Ensure that results are ordered by (surname,
firstname).</p>
<div class="highlight highlight-source-sql"><pre><span class="pl-k">SELECT</span> <span class="pl-c1">m</span>.<span class="pl-c1">firstname</span>, <span class="pl-c1">m</span>.<span class="pl-c1">surname</span>, <span class="pl-c1">r</span>.<span class="pl-c1">firstname</span>, <span class="pl-c1">r</span>.<span class="pl-c1">surname</span>
<span class="pl-k">FROM</span> members <span class="pl-k">AS</span> m
<span class="pl-k">LEFT OUTER JOIN</span> members <span class="pl-k">AS</span> r <span class="pl-k">ON</span> (<span class="pl-c1">m</span>.<span class="pl-c1">recommendedby</span> <span class="pl-k">=</span> <span class="pl-c1">r</span>.<span class="pl-c1">memid</span>)
<span class="pl-k">ORDER BY</span> <span class="pl-c1">m</span>.<span class="pl-c1">surname</span>, <span class="pl-c1">m</span>.<span class="pl-c1">firstname</span></pre></div>
<div class="highlight highlight-source-python"><pre><span class="pl-c1">MA</span> <span class="pl-k">=</span> Member.alias()
query <span class="pl-k">=</span> (Member
         .select(Member.firstname, Member.surname, <span class="pl-c1">MA</span>.firstname, <span class="pl-c1">MA</span>.surname)
         .join(<span class="pl-c1">MA</span>, <span class="pl-c1">JOIN</span>.<span class="pl-c1">LEFT_OUTER</span>, <span class="pl-v">on</span><span class="pl-k">=</span>(Member.recommendedby <span class="pl-k">==</span> <span class="pl-c1">MA</span>.memid))
         .order_by(Member.surname, Member.firstname))

<span class="pl-c"><span class="pl-c">#</span> To display the recommender's name when iterating:</span>
<span class="pl-k">for</span> m <span class="pl-k">in</span> query:
    <span class="pl-c1">print</span>(m.firstname, m.surname)
    <span class="pl-k">if</span> m.recommendedby:
        <span class="pl-c1">print</span>(<span class="pl-s"><span class="pl-pds">'</span>  <span class="pl-pds">'</span></span>, m.recommendedby.firstname, m.recommendedby.surname)</pre></div>
<a name="user-content-produce-a-list-of-all-members-who-have-used-a-tennis-court"></a>
<h3><a id="user-content-produce-a-list-of-all-members-who-have-used-a-tennis-court" class="anchor" aria-hidden="true" href="#produce-a-list-of-all-members-who-have-used-a-tennis-court"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Produce a list of all members who have used a tennis court</h3>
<p>How can you produce a list of all members who have used a tennis court?
Include in your output the name of the court, and the name of the member
formatted as a single column. Ensure no duplicate data, and order by the
member name.</p>
<div class="highlight highlight-source-sql"><pre><span class="pl-k">SELECT DISTINCT</span> <span class="pl-c1">m</span>.<span class="pl-c1">firstname</span> <span class="pl-k">||</span> <span class="pl-s"><span class="pl-pds">'</span> <span class="pl-pds">'</span></span> <span class="pl-k">||</span> <span class="pl-c1">m</span>.<span class="pl-c1">surname</span> <span class="pl-k">AS</span> member, <span class="pl-c1">f</span>.<span class="pl-c1">name</span> <span class="pl-k">AS</span> facility
<span class="pl-k">FROM</span> members <span class="pl-k">AS</span> m
<span class="pl-k">INNER JOIN</span> bookings <span class="pl-k">AS</span> b <span class="pl-k">ON</span> (<span class="pl-c1">m</span>.<span class="pl-c1">memid</span> <span class="pl-k">=</span> <span class="pl-c1">b</span>.<span class="pl-c1">memid</span>)
<span class="pl-k">INNER JOIN</span> facilities <span class="pl-k">AS</span> f <span class="pl-k">ON</span> (<span class="pl-c1">b</span>.<span class="pl-c1">facid</span> <span class="pl-k">=</span> <span class="pl-c1">f</span>.<span class="pl-c1">facid</span>)
<span class="pl-k">WHERE</span> <span class="pl-c1">f</span>.<span class="pl-c1">name</span> <span class="pl-k">LIKE</span> <span class="pl-s"><span class="pl-pds">'</span>Tennis%<span class="pl-pds">'</span></span>
<span class="pl-k">ORDER BY</span> member, facility;</pre></div>
<div class="highlight highlight-source-python"><pre>fullname <span class="pl-k">=</span> Member.firstname <span class="pl-k">+</span> <span class="pl-s"><span class="pl-pds">'</span> <span class="pl-pds">'</span></span> <span class="pl-k">+</span> Member.surname
query <span class="pl-k">=</span> (Member
         .select(fullname.alias(<span class="pl-s"><span class="pl-pds">'</span>member<span class="pl-pds">'</span></span>), Facility.name.alias(<span class="pl-s"><span class="pl-pds">'</span>facility<span class="pl-pds">'</span></span>))
         .join(Booking)
         .join(Facility)
         .where(Facility.name.startswith(<span class="pl-s"><span class="pl-pds">'</span>Tennis<span class="pl-pds">'</span></span>))
         .order_by(fullname, Facility.name)
         .distinct())</pre></div>
<a name="user-content-produce-a-list-of-costly-bookings"></a>
<h3><a id="user-content-produce-a-list-of-costly-bookings" class="anchor" aria-hidden="true" href="#produce-a-list-of-costly-bookings"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Produce a list of costly bookings</h3>
<p>How can you produce a list of bookings on the day of 2012-09-14 which will
cost the member (or guest) more than $30? Remember that guests have different
costs to members (the listed costs are per half-hour 'slot'), and the guest
user is always ID 0. Include in your output the name of the facility, the
name of the member formatted as a single column, and the cost. Order by
descending cost, and do not use any subqueries.</p>
<div class="highlight highlight-source-sql"><pre><span class="pl-k">SELECT</span> <span class="pl-c1">m</span>.<span class="pl-c1">firstname</span> <span class="pl-k">||</span> <span class="pl-s"><span class="pl-pds">'</span> <span class="pl-pds">'</span></span> <span class="pl-k">||</span> <span class="pl-c1">m</span>.<span class="pl-c1">surname</span> <span class="pl-k">AS</span> member,
       <span class="pl-c1">f</span>.<span class="pl-c1">name</span> <span class="pl-k">AS</span> facility,
       (CASE WHEN <span class="pl-c1">m</span>.<span class="pl-c1">memid</span> <span class="pl-k">=</span> <span class="pl-c1">0</span> THEN <span class="pl-c1">f</span>.<span class="pl-c1">guestcost</span> <span class="pl-k">*</span> <span class="pl-c1">b</span>.<span class="pl-c1">slots</span>
        ELSE <span class="pl-c1">f</span>.<span class="pl-c1">membercost</span> <span class="pl-k">*</span> <span class="pl-c1">b</span>.<span class="pl-c1">slots</span> END) <span class="pl-k">AS</span> cost
<span class="pl-k">FROM</span> members <span class="pl-k">AS</span> m
<span class="pl-k">INNER JOIN</span> bookings <span class="pl-k">AS</span> b <span class="pl-k">ON</span> (<span class="pl-c1">m</span>.<span class="pl-c1">memid</span> <span class="pl-k">=</span> <span class="pl-c1">b</span>.<span class="pl-c1">memid</span>)
<span class="pl-k">INNER JOIN</span> facilities <span class="pl-k">AS</span> f <span class="pl-k">ON</span> (<span class="pl-c1">b</span>.<span class="pl-c1">facid</span> <span class="pl-k">=</span> <span class="pl-c1">f</span>.<span class="pl-c1">facid</span>)
<span class="pl-k">WHERE</span> (date_trunc(<span class="pl-s"><span class="pl-pds">'</span>day<span class="pl-pds">'</span></span>, <span class="pl-c1">b</span>.<span class="pl-c1">starttime</span>) <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">'</span>2012-09-14<span class="pl-pds">'</span></span>) <span class="pl-k">AND</span>
 ((<span class="pl-c1">m</span>.<span class="pl-c1">memid</span> <span class="pl-k">=</span> <span class="pl-c1">0</span> <span class="pl-k">AND</span> <span class="pl-c1">b</span>.<span class="pl-c1">slots</span> <span class="pl-k">*</span> <span class="pl-c1">f</span>.<span class="pl-c1">guestcost</span> <span class="pl-k">&gt;</span> <span class="pl-c1">30</span>) <span class="pl-k">OR</span>
  (<span class="pl-c1">m</span>.<span class="pl-c1">memid</span> <span class="pl-k">&gt;</span> <span class="pl-c1">0</span> <span class="pl-k">AND</span> <span class="pl-c1">b</span>.<span class="pl-c1">slots</span> <span class="pl-k">*</span> <span class="pl-c1">f</span>.<span class="pl-c1">membercost</span> <span class="pl-k">&gt;</span> <span class="pl-c1">30</span>))
<span class="pl-k">ORDER BY</span> cost <span class="pl-k">DESC</span>;</pre></div>
<div class="highlight highlight-source-python"><pre>cost <span class="pl-k">=</span> Case(Member.memid, (
    (<span class="pl-c1">0</span>, Booking.slots <span class="pl-k">*</span> Facility.guestcost),
), (Booking.slots <span class="pl-k">*</span> Facility.membercost))
fullname <span class="pl-k">=</span> Member.firstname <span class="pl-k">+</span> <span class="pl-s"><span class="pl-pds">'</span> <span class="pl-pds">'</span></span> <span class="pl-k">+</span> Member.surname

query <span class="pl-k">=</span> (Member
         .select(fullname.alias(<span class="pl-s"><span class="pl-pds">'</span>member<span class="pl-pds">'</span></span>), Facility.name.alias(<span class="pl-s"><span class="pl-pds">'</span>facility<span class="pl-pds">'</span></span>),
                 cost.alias(<span class="pl-s"><span class="pl-pds">'</span>cost<span class="pl-pds">'</span></span>))
         .join(Booking)
         .join(Facility)
         .where(
             (fn.date_trunc(<span class="pl-s"><span class="pl-pds">'</span>day<span class="pl-pds">'</span></span>, Booking.starttime) <span class="pl-k">==</span> datetime.date(<span class="pl-c1">2012</span>, <span class="pl-c1">9</span>, <span class="pl-c1">14</span>)) <span class="pl-k">&amp;</span>
             (cost <span class="pl-k">&gt;</span> <span class="pl-c1">30</span>))
         .order_by(SQL(<span class="pl-s"><span class="pl-pds">'</span>cost<span class="pl-pds">'</span></span>).desc()))

<span class="pl-c"><span class="pl-c">#</span> To iterate over the results, it might be easiest to use namedtuples:</span>
<span class="pl-k">for</span> row <span class="pl-k">in</span> query.namedtuples():
    <span class="pl-c1">print</span>(row.member, row.facility, row.cost)</pre></div>
<a name="user-content-produce-a-list-of-all-members-along-with-their-recommender-using-no-joins"></a>
<h3><a id="user-content-produce-a-list-of-all-members-along-with-their-recommender-using-no-joins" class="anchor" aria-hidden="true" href="#produce-a-list-of-all-members-along-with-their-recommender-using-no-joins"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Produce a list of all members, along with their recommender, using no joins.</h3>
<p>How can you output a list of all members, including the individual who
recommended them (if any), without using any joins? Ensure that there are no
duplicates in the list, and that each firstname + surname pairing is
formatted as a column and ordered.</p>
<div class="highlight highlight-source-sql"><pre><span class="pl-k">SELECT DISTINCT</span> <span class="pl-c1">m</span>.<span class="pl-c1">firstname</span> <span class="pl-k">||</span> <span class="pl-s"><span class="pl-pds">'</span> <span class="pl-pds">'</span></span> <span class="pl-k">||</span> <span class="pl-c1">m</span>.<span class="pl-c1">surname</span> <span class="pl-k">AS</span> member,
   (<span class="pl-k">SELECT</span> <span class="pl-c1">r</span>.<span class="pl-c1">firstname</span> <span class="pl-k">||</span> <span class="pl-s"><span class="pl-pds">'</span> <span class="pl-pds">'</span></span> <span class="pl-k">||</span> <span class="pl-c1">r</span>.<span class="pl-c1">surname</span>
    <span class="pl-k">FROM</span> <span class="pl-c1">cd</span>.<span class="pl-c1">members</span> <span class="pl-k">AS</span> r
    <span class="pl-k">WHERE</span> <span class="pl-c1">m</span>.<span class="pl-c1">recommendedby</span> <span class="pl-k">=</span> <span class="pl-c1">r</span>.<span class="pl-c1">memid</span>) <span class="pl-k">AS</span> recommended
<span class="pl-k">FROM</span> members <span class="pl-k">AS</span> m <span class="pl-k">ORDER BY</span> member;</pre></div>
<div class="highlight highlight-source-python"><pre><span class="pl-c1">MA</span> <span class="pl-k">=</span> Member.alias()
subq <span class="pl-k">=</span> (<span class="pl-c1">MA</span>
        .select(<span class="pl-c1">MA</span>.firstname <span class="pl-k">+</span> <span class="pl-s"><span class="pl-pds">'</span> <span class="pl-pds">'</span></span> <span class="pl-k">+</span> <span class="pl-c1">MA</span>.surname)
        .where(Member.recommendedby <span class="pl-k">==</span> <span class="pl-c1">MA</span>.memid))
query <span class="pl-k">=</span> (Member
         .select(fullname.alias(<span class="pl-s"><span class="pl-pds">'</span>member<span class="pl-pds">'</span></span>), subq.alias(<span class="pl-s"><span class="pl-pds">'</span>recommended<span class="pl-pds">'</span></span>))
         .order_by(fullname))</pre></div>
<a name="user-content-produce-a-list-of-costly-bookings-using-a-subquery"></a>
<h3><a id="user-content-produce-a-list-of-costly-bookings-using-a-subquery" class="anchor" aria-hidden="true" href="#produce-a-list-of-costly-bookings-using-a-subquery"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Produce a list of costly bookings, using a subquery</h3>
<p>The "Produce a list of costly bookings" exercise contained some messy logic: we
had to calculate the booking cost in both the WHERE clause and the CASE
statement. Try to simplify this calculation using subqueries.</p>
<div class="highlight highlight-source-sql"><pre><span class="pl-k">SELECT</span> member, facility, cost <span class="pl-k">from</span> (
  <span class="pl-k">SELECT</span>
  <span class="pl-c1">m</span>.<span class="pl-c1">firstname</span> <span class="pl-k">||</span> <span class="pl-s"><span class="pl-pds">'</span> <span class="pl-pds">'</span></span> <span class="pl-k">||</span> <span class="pl-c1">m</span>.<span class="pl-c1">surname</span> <span class="pl-k">as</span> member,
  <span class="pl-c1">f</span>.<span class="pl-c1">name</span> <span class="pl-k">as</span> facility,
  CASE WHEN <span class="pl-c1">m</span>.<span class="pl-c1">memid</span> <span class="pl-k">=</span> <span class="pl-c1">0</span> THEN <span class="pl-c1">b</span>.<span class="pl-c1">slots</span> <span class="pl-k">*</span> <span class="pl-c1">f</span>.<span class="pl-c1">guestcost</span>
  ELSE <span class="pl-c1">b</span>.<span class="pl-c1">slots</span> <span class="pl-k">*</span> <span class="pl-c1">f</span>.<span class="pl-c1">membercost</span> END <span class="pl-k">AS</span> cost
  <span class="pl-k">FROM</span> members <span class="pl-k">AS</span> m
  <span class="pl-k">INNER JOIN</span> bookings <span class="pl-k">AS</span> b <span class="pl-k">ON</span> <span class="pl-c1">m</span>.<span class="pl-c1">memid</span> <span class="pl-k">=</span> <span class="pl-c1">b</span>.<span class="pl-c1">memid</span>
  <span class="pl-k">INNER JOIN</span> facilities <span class="pl-k">AS</span> f <span class="pl-k">ON</span> <span class="pl-c1">b</span>.<span class="pl-c1">facid</span> <span class="pl-k">=</span> <span class="pl-c1">f</span>.<span class="pl-c1">facid</span>
  <span class="pl-k">WHERE</span> date_trunc(<span class="pl-s"><span class="pl-pds">'</span>day<span class="pl-pds">'</span></span>, <span class="pl-c1">b</span>.<span class="pl-c1">starttime</span>) <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">'</span>2012-09-14<span class="pl-pds">'</span></span>
) <span class="pl-k">as</span> bookings
<span class="pl-k">WHERE</span> cost <span class="pl-k">&gt;</span> <span class="pl-c1">30</span>
<span class="pl-k">ORDER BY</span> cost <span class="pl-k">DESC</span>;</pre></div>
<div class="highlight highlight-source-python"><pre>cost <span class="pl-k">=</span> Case(Member.memid, (
    (<span class="pl-c1">0</span>, Booking.slots <span class="pl-k">*</span> Facility.guestcost),
), (Booking.slots <span class="pl-k">*</span> Facility.membercost))

iq <span class="pl-k">=</span> (Member
      .select(fullname.alias(<span class="pl-s"><span class="pl-pds">'</span>member<span class="pl-pds">'</span></span>), Facility.name.alias(<span class="pl-s"><span class="pl-pds">'</span>facility<span class="pl-pds">'</span></span>),
              cost.alias(<span class="pl-s"><span class="pl-pds">'</span>cost<span class="pl-pds">'</span></span>))
      .join(Booking)
      .join(Facility)
      .where(fn.date_trunc(<span class="pl-s"><span class="pl-pds">'</span>day<span class="pl-pds">'</span></span>, Booking.starttime) <span class="pl-k">==</span> datetime.date(<span class="pl-c1">2012</span>, <span class="pl-c1">9</span>, <span class="pl-c1">14</span>)))

query <span class="pl-k">=</span> (Member
         .select(iq.c.member, iq.c.facility, iq.c.cost)
         .from_(iq)
         .where(iq.c.cost <span class="pl-k">&gt;</span> <span class="pl-c1">30</span>)
         .order_by(SQL(<span class="pl-s"><span class="pl-pds">'</span>cost<span class="pl-pds">'</span></span>).desc()))

<span class="pl-c"><span class="pl-c">#</span> To iterate, try using dicts:</span>
<span class="pl-k">for</span> row <span class="pl-k">in</span> query.dicts():
    <span class="pl-c1">print</span>(row[<span class="pl-s"><span class="pl-pds">'</span>member<span class="pl-pds">'</span></span>], row[<span class="pl-s"><span class="pl-pds">'</span>facility<span class="pl-pds">'</span></span>], row[<span class="pl-s"><span class="pl-pds">'</span>cost<span class="pl-pds">'</span></span>])</pre></div>
<a name="user-content-modifying-data"></a>
<h2><a id="user-content-modifying-data" class="anchor" aria-hidden="true" href="#modifying-data"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Modifying Data</h2>
<p>Querying data is all well and good, but at some point you're probably going to
want to put data into your database! This section deals with inserting,
updating, and deleting information. Operations that alter your data like this
are collectively known as Data Manipulation Language, or DML.</p>
<p>In previous sections, we returned to you the results of the query you've
performed. Since modifications like the ones we're making in this section don't
return any query results, we instead show you the updated content of the table
you're supposed to be working on.</p>
<a name="user-content-insert-some-data-into-a-table"></a>
<h3><a id="user-content-insert-some-data-into-a-table" class="anchor" aria-hidden="true" href="#insert-some-data-into-a-table"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Insert some data into a table</h3>
<p>The club is adding a new facility - a spa. We need to add it into the
facilities table. Use the following values: facid: 9, Name: 'Spa',
membercost: 20, guestcost: 30, initialoutlay: 100000, monthlymaintenance: 800</p>
<div class="highlight highlight-source-sql"><pre><span class="pl-k">INSERT INTO</span> <span class="pl-s"><span class="pl-pds">"</span>facilities<span class="pl-pds">"</span></span> (<span class="pl-s"><span class="pl-pds">"</span>facid<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>name<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>membercost<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>guestcost<span class="pl-pds">"</span></span>,
<span class="pl-s"><span class="pl-pds">"</span>initialoutlay<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>monthlymaintenance<span class="pl-pds">"</span></span>) <span class="pl-k">VALUES</span> (<span class="pl-c1">9</span>, <span class="pl-s"><span class="pl-pds">'</span>Spa<span class="pl-pds">'</span></span>, <span class="pl-c1">20</span>, <span class="pl-c1">30</span>, <span class="pl-c1">100000</span>, <span class="pl-c1">800</span>)</pre></div>
<div class="highlight highlight-source-python"><pre>res <span class="pl-k">=</span> Facility.insert({
    Facility.facid: <span class="pl-c1">9</span>,
    Facility.name: <span class="pl-s"><span class="pl-pds">'</span>Spa<span class="pl-pds">'</span></span>,
    Facility.membercost: <span class="pl-c1">20</span>,
    Facility.guestcost: <span class="pl-c1">30</span>,
    Facility.initialoutlay: <span class="pl-c1">100000</span>,
    Facility.monthlymaintenance: <span class="pl-c1">800</span>}).execute()

<span class="pl-c"><span class="pl-c">#</span> OR:</span>
res <span class="pl-k">=</span> (Facility
       .insert(<span class="pl-v">facid</span><span class="pl-k">=</span><span class="pl-c1">9</span>, <span class="pl-v">name</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">'</span>Spa<span class="pl-pds">'</span></span>, <span class="pl-v">membercost</span><span class="pl-k">=</span><span class="pl-c1">20</span>, <span class="pl-v">guestcost</span><span class="pl-k">=</span><span class="pl-c1">30</span>,
               <span class="pl-v">initialoutlay</span><span class="pl-k">=</span><span class="pl-c1">100000</span>, <span class="pl-v">monthlymaintenance</span><span class="pl-k">=</span><span class="pl-c1">800</span>)
       .execute())</pre></div>
<a name="user-content-insert-multiple-rows-of-data-into-a-table"></a>
<h3><a id="user-content-insert-multiple-rows-of-data-into-a-table" class="anchor" aria-hidden="true" href="#insert-multiple-rows-of-data-into-a-table"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Insert multiple rows of data into a table</h3>
<p>In the previous exercise, you learned how to add a facility. Now you're going
to add multiple facilities in one command. Use the following values:</p>
<p>facid: 9, Name: 'Spa', membercost: 20, guestcost: 30, initialoutlay: 100000,
monthlymaintenance: 800.</p>
<p>facid: 10, Name: 'Squash Court 2', membercost: 3.5, guestcost: 17.5,
initialoutlay: 5000, monthlymaintenance: 80.</p>
<div class="highlight highlight-source-sql"><pre><span class="pl-c"><span class="pl-c">--</span> see above --</span></pre></div>
<div class="highlight highlight-source-python"><pre>data <span class="pl-k">=</span> [
    {<span class="pl-s"><span class="pl-pds">'</span>facid<span class="pl-pds">'</span></span>: <span class="pl-c1">9</span>, <span class="pl-s"><span class="pl-pds">'</span>name<span class="pl-pds">'</span></span>: <span class="pl-s"><span class="pl-pds">'</span>Spa<span class="pl-pds">'</span></span>, <span class="pl-s"><span class="pl-pds">'</span>membercost<span class="pl-pds">'</span></span>: <span class="pl-c1">20</span>, <span class="pl-s"><span class="pl-pds">'</span>guestcost<span class="pl-pds">'</span></span>: <span class="pl-c1">30</span>,
     <span class="pl-s"><span class="pl-pds">'</span>initialoutlay<span class="pl-pds">'</span></span>: <span class="pl-c1">100000</span>, <span class="pl-s"><span class="pl-pds">'</span>monthlymaintenance<span class="pl-pds">'</span></span>: <span class="pl-c1">800</span>},
    {<span class="pl-s"><span class="pl-pds">'</span>facid<span class="pl-pds">'</span></span>: <span class="pl-c1">10</span>, <span class="pl-s"><span class="pl-pds">'</span>name<span class="pl-pds">'</span></span>: <span class="pl-s"><span class="pl-pds">'</span>Squash Court 2<span class="pl-pds">'</span></span>, <span class="pl-s"><span class="pl-pds">'</span>membercost<span class="pl-pds">'</span></span>: <span class="pl-c1">3.5</span>,
     <span class="pl-s"><span class="pl-pds">'</span>guestcost<span class="pl-pds">'</span></span>: <span class="pl-c1">17.5</span>, <span class="pl-s"><span class="pl-pds">'</span>initialoutlay<span class="pl-pds">'</span></span>: <span class="pl-c1">5000</span>, <span class="pl-s"><span class="pl-pds">'</span>monthlymaintenance<span class="pl-pds">'</span></span>: <span class="pl-c1">80</span>}]
res <span class="pl-k">=</span> Facility.insert_many(data).execute()</pre></div>
<a name="user-content-insert-calculated-data-into-a-table"></a>
<h3><a id="user-content-insert-calculated-data-into-a-table" class="anchor" aria-hidden="true" href="#insert-calculated-data-into-a-table"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Insert calculated data into a table</h3>
<p>Let's try adding the spa to the facilities table again. This time, though, we
want to automatically generate the value for the next facid, rather than
specifying it as a constant. Use the following values for everything else:
Name: 'Spa', membercost: 20, guestcost: 30, initialoutlay: 100000,
monthlymaintenance: 800.</p>
<div class="highlight highlight-source-sql"><pre><span class="pl-k">INSERT INTO</span> <span class="pl-s"><span class="pl-pds">"</span>facilities<span class="pl-pds">"</span></span> (<span class="pl-s"><span class="pl-pds">"</span>facid<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>name<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>membercost<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>guestcost<span class="pl-pds">"</span></span>,
  <span class="pl-s"><span class="pl-pds">"</span>initialoutlay<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>monthlymaintenance<span class="pl-pds">"</span></span>)
<span class="pl-k">SELECT</span> (<span class="pl-k">SELECT</span> (<span class="pl-c1">MAX</span>(<span class="pl-s"><span class="pl-pds">"</span>facid<span class="pl-pds">"</span></span>) <span class="pl-k">+</span> <span class="pl-c1">1</span>) <span class="pl-k">FROM</span> <span class="pl-s"><span class="pl-pds">"</span>facilities<span class="pl-pds">"</span></span>) <span class="pl-k">AS</span> _,
        <span class="pl-s"><span class="pl-pds">'</span>Spa<span class="pl-pds">'</span></span>, <span class="pl-c1">20</span>, <span class="pl-c1">30</span>, <span class="pl-c1">100000</span>, <span class="pl-c1">800</span>;</pre></div>
<div class="highlight highlight-source-python"><pre>maxq <span class="pl-k">=</span> Facility.select(fn.MAX(Facility.facid) <span class="pl-k">+</span> <span class="pl-c1">1</span>)
subq <span class="pl-k">=</span> Select(<span class="pl-v">columns</span><span class="pl-k">=</span>(maxq, <span class="pl-s"><span class="pl-pds">'</span>Spa<span class="pl-pds">'</span></span>, <span class="pl-c1">20</span>, <span class="pl-c1">30</span>, <span class="pl-c1">100000</span>, <span class="pl-c1">800</span>))
res <span class="pl-k">=</span> Facility.insert_from(subq, Facility._meta.sorted_fields).execute()</pre></div>
<a name="user-content-update-some-existing-data"></a>
<h3><a id="user-content-update-some-existing-data" class="anchor" aria-hidden="true" href="#update-some-existing-data"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Update some existing data</h3>
<p>We made a mistake when entering the data for the second tennis court. The
initial outlay was 10000 rather than 8000: you need to alter the data to fix
the error.</p>
<div class="highlight highlight-source-sql"><pre><span class="pl-k">UPDATE</span> facilities <span class="pl-k">SET</span> initialoutlay <span class="pl-k">=</span> <span class="pl-c1">10000</span> <span class="pl-k">WHERE</span> name <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">'</span>Tennis Court 2<span class="pl-pds">'</span></span>;</pre></div>
<div class="highlight highlight-source-python"><pre>res <span class="pl-k">=</span> (Facility
       .update({Facility.initialoutlay: <span class="pl-c1">10000</span>})
       .where(Facility.name <span class="pl-k">==</span> <span class="pl-s"><span class="pl-pds">'</span>Tennis Court 2<span class="pl-pds">'</span></span>)
       .execute())

<span class="pl-c"><span class="pl-c">#</span> OR:</span>
res <span class="pl-k">=</span> (Facility
       .update(<span class="pl-v">initialoutlay</span><span class="pl-k">=</span><span class="pl-c1">10000</span>)
       .where(Facility.name <span class="pl-k">==</span> <span class="pl-s"><span class="pl-pds">'</span>Tennis Court 2<span class="pl-pds">'</span></span>)
       .execute())</pre></div>
<a name="user-content-update-multiple-rows-and-columns-at-the-same-time"></a>
<h3><a id="user-content-update-multiple-rows-and-columns-at-the-same-time" class="anchor" aria-hidden="true" href="#update-multiple-rows-and-columns-at-the-same-time"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Update multiple rows and columns at the same time</h3>
<p>We want to increase the price of the tennis courts for both members and
guests. Update the costs to be 6 for members, and 30 for guests.</p>
<div class="highlight highlight-source-sql"><pre><span class="pl-k">UPDATE</span> facilities <span class="pl-k">SET</span> membercost<span class="pl-k">=</span><span class="pl-c1">6</span>, guestcost<span class="pl-k">=</span><span class="pl-c1">30</span> <span class="pl-k">WHERE</span> name ILIKE <span class="pl-s"><span class="pl-pds">'</span>Tennis%<span class="pl-pds">'</span></span>;</pre></div>
<div class="highlight highlight-source-python"><pre>nrows <span class="pl-k">=</span> (Facility
         .update(<span class="pl-v">membercost</span><span class="pl-k">=</span><span class="pl-c1">6</span>, <span class="pl-v">guestcost</span><span class="pl-k">=</span><span class="pl-c1">30</span>)
         .where(Facility.name.startswith(<span class="pl-s"><span class="pl-pds">'</span>Tennis<span class="pl-pds">'</span></span>))
         .execute())</pre></div>
<a name="user-content-update-a-row-based-on-the-contents-of-another-row"></a>
<h3><a id="user-content-update-a-row-based-on-the-contents-of-another-row" class="anchor" aria-hidden="true" href="#update-a-row-based-on-the-contents-of-another-row"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Update a row based on the contents of another row</h3>
<p>We want to alter the price of the second tennis court so that it costs 10%
more than the first one. Try to do this without using constant values for the
prices, so that we can reuse the statement if we want to.</p>
<div class="highlight highlight-source-sql"><pre><span class="pl-k">UPDATE</span> facilities <span class="pl-k">SET</span>
membercost <span class="pl-k">=</span> (<span class="pl-k">SELECT</span> membercost <span class="pl-k">*</span> <span class="pl-c1">1</span>.<span class="pl-c1">1</span> <span class="pl-k">FROM</span> facilities <span class="pl-k">WHERE</span> facid <span class="pl-k">=</span> <span class="pl-c1">0</span>),
guestcost <span class="pl-k">=</span> (<span class="pl-k">SELECT</span> guestcost <span class="pl-k">*</span> <span class="pl-c1">1</span>.<span class="pl-c1">1</span> <span class="pl-k">FROM</span> facilities <span class="pl-k">WHERE</span> facid <span class="pl-k">=</span> <span class="pl-c1">0</span>)
<span class="pl-k">WHERE</span> facid <span class="pl-k">=</span> <span class="pl-c1">1</span>;

<span class="pl-c"><span class="pl-c">--</span> OR --</span>
WITH new_prices (nmc, ngc) <span class="pl-k">AS</span> (
  <span class="pl-k">SELECT</span> membercost <span class="pl-k">*</span> <span class="pl-c1">1</span>.<span class="pl-c1">1</span>, guestcost <span class="pl-k">*</span> <span class="pl-c1">1</span>.<span class="pl-c1">1</span>
  <span class="pl-k">FROM</span> facilities <span class="pl-k">WHERE</span> name <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">'</span>Tennis Court 1<span class="pl-pds">'</span></span>)
<span class="pl-k">UPDATE</span> facilities
<span class="pl-k">SET</span> membercost <span class="pl-k">=</span> <span class="pl-c1">new_prices</span>.<span class="pl-c1">nmc</span>, guestcost <span class="pl-k">=</span> <span class="pl-c1">new_prices</span>.<span class="pl-c1">ngc</span>
<span class="pl-k">FROM</span> new_prices
<span class="pl-k">WHERE</span> name <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">'</span>Tennis Court 2<span class="pl-pds">'</span></span></pre></div>
<div class="highlight highlight-source-python"><pre>sq1 <span class="pl-k">=</span> Facility.select(Facility.membercost <span class="pl-k">*</span> <span class="pl-c1">1.1</span>).where(Facility.facid <span class="pl-k">==</span> <span class="pl-c1">0</span>)
sq2 <span class="pl-k">=</span> Facility.select(Facility.guestcost <span class="pl-k">*</span> <span class="pl-c1">1.1</span>).where(Facility.facid <span class="pl-k">==</span> <span class="pl-c1">0</span>)

res <span class="pl-k">=</span> (Facility
       .update(<span class="pl-v">membercost</span><span class="pl-k">=</span>sq1, <span class="pl-v">guestcost</span><span class="pl-k">=</span>sq2)
       .where(Facility.facid <span class="pl-k">==</span> <span class="pl-c1">1</span>)
       .execute())

<span class="pl-c"><span class="pl-c">#</span> OR:</span>
cte <span class="pl-k">=</span> (Facility
       .select(Facility.membercost <span class="pl-k">*</span> <span class="pl-c1">1.1</span>, Facility.guestcost <span class="pl-k">*</span> <span class="pl-c1">1.1</span>)
       .where(Facility.name <span class="pl-k">==</span> <span class="pl-s"><span class="pl-pds">'</span>Tennis Court 1<span class="pl-pds">'</span></span>)
       .cte(<span class="pl-s"><span class="pl-pds">'</span>new_prices<span class="pl-pds">'</span></span>, <span class="pl-v">columns</span><span class="pl-k">=</span>(<span class="pl-s"><span class="pl-pds">'</span>nmc<span class="pl-pds">'</span></span>, <span class="pl-s"><span class="pl-pds">'</span>ngc<span class="pl-pds">'</span></span>)))
res <span class="pl-k">=</span> (Facility
       .update(<span class="pl-v">membercost</span><span class="pl-k">=</span>SQL(<span class="pl-s"><span class="pl-pds">'</span>new_prices.nmc<span class="pl-pds">'</span></span>), <span class="pl-v">guestcost</span><span class="pl-k">=</span>SQL(<span class="pl-s"><span class="pl-pds">'</span>new_prices.ngc<span class="pl-pds">'</span></span>))
       .with_cte(cte)
       .from_(cte)
       .where(Facility.name <span class="pl-k">==</span> <span class="pl-s"><span class="pl-pds">'</span>Tennis Court 2<span class="pl-pds">'</span></span>)
       .execute())</pre></div>
<a name="user-content-delete-all-bookings"></a>
<h3><a id="user-content-delete-all-bookings" class="anchor" aria-hidden="true" href="#delete-all-bookings"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Delete all bookings</h3>
<p>As part of a clearout of our database, we want to delete all bookings from
the bookings table.</p>
<div class="highlight highlight-source-sql"><pre><span class="pl-k">DELETE</span> <span class="pl-k">FROM</span> bookings;</pre></div>
<div class="highlight highlight-source-python"><pre>nrows <span class="pl-k">=</span> Booking.delete().execute()</pre></div>
<a name="user-content-delete-a-member-from-the-cd-members-table"></a>
<h3><a id="user-content-delete-a-member-from-the-cdmembers-table" class="anchor" aria-hidden="true" href="#delete-a-member-from-the-cdmembers-table"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Delete a member from the cd.members table</h3>
<p>We want to remove member 37, who has never made a booking, from our database.</p>
<div class="highlight highlight-source-sql"><pre><span class="pl-k">DELETE</span> <span class="pl-k">FROM</span> members <span class="pl-k">WHERE</span> memid <span class="pl-k">=</span> <span class="pl-c1">37</span>;</pre></div>
<div class="highlight highlight-source-python"><pre>nrows <span class="pl-k">=</span> Member.delete().where(Member.memid <span class="pl-k">==</span> <span class="pl-c1">37</span>).execute()</pre></div>
<a name="user-content-delete-based-on-a-subquery"></a>
<h3><a id="user-content-delete-based-on-a-subquery" class="anchor" aria-hidden="true" href="#delete-based-on-a-subquery"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Delete based on a subquery</h3>
<p>How can we make that more general, to delete all members who have never made
a booking?</p>
<div class="highlight highlight-source-sql"><pre><span class="pl-k">DELETE</span> <span class="pl-k">FROM</span> members <span class="pl-k">WHERE</span> NOT EXISTS (
  <span class="pl-k">SELECT</span> <span class="pl-k">*</span> <span class="pl-k">FROM</span> bookings <span class="pl-k">WHERE</span> <span class="pl-c1">bookings</span>.<span class="pl-c1">memid</span> <span class="pl-k">=</span> <span class="pl-c1">members</span>.<span class="pl-c1">memid</span>);</pre></div>
<div class="highlight highlight-source-python"><pre>subq <span class="pl-k">=</span> Booking.select().where(Booking.member <span class="pl-k">==</span> Member.memid)
nrows <span class="pl-k">=</span> Member.delete().where(<span class="pl-k">~</span>fn.EXISTS(subq)).execute()</pre></div>
<a name="user-content-aggregation"></a>
<h2><a id="user-content-aggregation" class="anchor" aria-hidden="true" href="#aggregation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Aggregation</h2>
<p>Aggregation is one of those capabilities that really make you appreciate the
power of relational database systems. It allows you to move beyond merely
persisting your data, into the realm of asking truly interesting questions that
can be used to inform decision making. This category covers aggregation at
length, making use of standard grouping as well as more recent window
functions.</p>
<a name="user-content-count-the-number-of-facilities"></a>
<h3><a id="user-content-count-the-number-of-facilities" class="anchor" aria-hidden="true" href="#count-the-number-of-facilities"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Count the number of facilities</h3>
<p>For our first foray into aggregates, we're going to stick to something
simple. We want to know how many facilities exist - simply produce a total
count.</p>
<div class="highlight highlight-source-sql"><pre><span class="pl-k">SELECT</span> <span class="pl-c1">COUNT</span>(facid) <span class="pl-k">FROM</span> facilities;</pre></div>
<div class="highlight highlight-source-python"><pre>query <span class="pl-k">=</span> Facility.select(fn.COUNT(Facility.facid))
count <span class="pl-k">=</span> query.scalar()

<span class="pl-c"><span class="pl-c">#</span> OR:</span>
count <span class="pl-k">=</span> Facility.select().count()</pre></div>
<a name="user-content-count-the-number-of-expensive-facilities"></a>
<h3><a id="user-content-count-the-number-of-expensive-facilities" class="anchor" aria-hidden="true" href="#count-the-number-of-expensive-facilities"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Count the number of expensive facilities</h3>
<p>Produce a count of the number of facilities that have a cost to guests of 10
or more.</p>
<div class="highlight highlight-source-sql"><pre><span class="pl-k">SELECT</span> <span class="pl-c1">COUNT</span>(facid) <span class="pl-k">FROM</span> facilities <span class="pl-k">WHERE</span> guestcost <span class="pl-k">&gt;=</span> <span class="pl-c1">10</span></pre></div>
<div class="highlight highlight-source-python"><pre>query <span class="pl-k">=</span> Facility.select(fn.COUNT(Facility.facid)).where(Facility.guestcost <span class="pl-k">&gt;=</span> <span class="pl-c1">10</span>)
count <span class="pl-k">=</span> query.scalar()

<span class="pl-c"><span class="pl-c">#</span> OR:</span>
<span class="pl-c"><span class="pl-c">#</span> count = Facility.select().where(Facility.guestcost &gt;= 10).count()</span></pre></div>
<a name="user-content-count-the-number-of-recommendations-each-member-makes"></a>
<h3><a id="user-content-count-the-number-of-recommendations-each-member-makes" class="anchor" aria-hidden="true" href="#count-the-number-of-recommendations-each-member-makes"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Count the number of recommendations each member makes.</h3>
<p>Produce a count of the number of recommendations each member has made. Order
by member ID.</p>
<div class="highlight highlight-source-sql"><pre><span class="pl-k">SELECT</span> recommendedby, <span class="pl-c1">COUNT</span>(memid) <span class="pl-k">FROM</span> members
<span class="pl-k">WHERE</span> recommendedby <span class="pl-k">IS NOT NULL</span>
<span class="pl-k">GROUP BY</span> recommendedby
<span class="pl-k">ORDER BY</span> recommendedby</pre></div>
<div class="highlight highlight-source-python"><pre>query <span class="pl-k">=</span> (Member
         .select(Member.recommendedby, fn.COUNT(Member.memid))
         .where(Member.recommendedby.is_null(<span class="pl-c1">False</span>))
         .group_by(Member.recommendedby)
         .order_by(Member.recommendedby))</pre></div>
<a name="user-content-list-the-total-slots-booked-per-facility"></a>
<h3><a id="user-content-list-the-total-slots-booked-per-facility" class="anchor" aria-hidden="true" href="#list-the-total-slots-booked-per-facility"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>List the total slots booked per facility</h3>
<p>Produce a list of the total number of slots booked per facility. For now,
just produce an output table consisting of facility id and slots, sorted by
facility id.</p>
<div class="highlight highlight-source-sql"><pre><span class="pl-k">SELECT</span> facid, <span class="pl-c1">SUM</span>(slots) <span class="pl-k">FROM</span> bookings <span class="pl-k">GROUP BY</span> facid <span class="pl-k">ORDER BY</span> facid;</pre></div>
<div class="highlight highlight-source-python"><pre>query <span class="pl-k">=</span> (Booking
         .select(Booking.facid, fn.SUM(Booking.slots))
         .group_by(Booking.facid)
         .order_by(Booking.facid))</pre></div>
<a name="user-content-list-the-total-slots-booked-per-facility-in-a-given-month"></a>
<h3><a id="user-content-list-the-total-slots-booked-per-facility-in-a-given-month" class="anchor" aria-hidden="true" href="#list-the-total-slots-booked-per-facility-in-a-given-month"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>List the total slots booked per facility in a given month</h3>
<p>Produce a list of the total number of slots booked per facility in the month
of September 2012. Produce an output table consisting of facility id and
slots, sorted by the number of slots.</p>
<div class="highlight highlight-source-sql"><pre><span class="pl-k">SELECT</span> facid, <span class="pl-c1">SUM</span>(slots)
<span class="pl-k">FROM</span> bookings
<span class="pl-k">WHERE</span> (date_trunc(<span class="pl-s"><span class="pl-pds">'</span>month<span class="pl-pds">'</span></span>, starttime) <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">'</span>2012-09-01<span class="pl-pds">'</span></span>::dates)
<span class="pl-k">GROUP BY</span> facid
<span class="pl-k">ORDER BY</span> <span class="pl-c1">SUM</span>(slots)</pre></div>
<div class="highlight highlight-source-python"><pre>query <span class="pl-k">=</span> (Booking
         .select(Booking.facility, fn.SUM(Booking.slots))
         .where(fn.date_trunc(<span class="pl-s"><span class="pl-pds">'</span>month<span class="pl-pds">'</span></span>, Booking.starttime) <span class="pl-k">==</span> datetime.date(<span class="pl-c1">2012</span>, <span class="pl-c1">9</span>, <span class="pl-c1">1</span>))
         .group_by(Booking.facility)
         .order_by(fn.SUM(Booking.slots)))</pre></div>
<a name="user-content-list-the-total-slots-booked-per-facility-per-month"></a>
<h3><a id="user-content-list-the-total-slots-booked-per-facility-per-month" class="anchor" aria-hidden="true" href="#list-the-total-slots-booked-per-facility-per-month"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>List the total slots booked per facility per month</h3>
<p>Produce a list of the total number of slots booked per facility per month in
the year of 2012. Produce an output table consisting of facility id and
slots, sorted by the id and month.</p>
<div class="highlight highlight-source-sql"><pre><span class="pl-k">SELECT</span> facid, date_part(<span class="pl-s"><span class="pl-pds">'</span>month<span class="pl-pds">'</span></span>, starttime), <span class="pl-c1">SUM</span>(slots)
<span class="pl-k">FROM</span> bookings
<span class="pl-k">WHERE</span> date_part(<span class="pl-s"><span class="pl-pds">'</span>year<span class="pl-pds">'</span></span>, starttime) <span class="pl-k">=</span> <span class="pl-c1">2012</span>
<span class="pl-k">GROUP BY</span> facid, date_part(<span class="pl-s"><span class="pl-pds">'</span>month<span class="pl-pds">'</span></span>, starttime)
<span class="pl-k">ORDER BY</span> facid, date_part(<span class="pl-s"><span class="pl-pds">'</span>month<span class="pl-pds">'</span></span>, starttime)</pre></div>
<div class="highlight highlight-source-python"><pre>month <span class="pl-k">=</span> fn.date_part(<span class="pl-s"><span class="pl-pds">'</span>month<span class="pl-pds">'</span></span>, Booking.starttime)
query <span class="pl-k">=</span> (Booking
         .select(Booking.facility, month, fn.SUM(Booking.slots))
         .where(fn.date_part(<span class="pl-s"><span class="pl-pds">'</span>year<span class="pl-pds">'</span></span>, Booking.starttime) <span class="pl-k">==</span> <span class="pl-c1">2012</span>)
         .group_by(Booking.facility, month)
         .order_by(Booking.facility, month))</pre></div>
<a name="user-content-find-the-count-of-members-who-have-made-at-least-one-booking"></a>
<h3><a id="user-content-find-the-count-of-members-who-have-made-at-least-one-booking" class="anchor" aria-hidden="true" href="#find-the-count-of-members-who-have-made-at-least-one-booking"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Find the count of members who have made at least one booking</h3>
<p>Find the total number of members who have made at least one booking.</p>
<div class="highlight highlight-source-sql"><pre><span class="pl-k">SELECT</span> <span class="pl-c1">COUNT</span>(DISTINCT memid) <span class="pl-k">FROM</span> bookings

<span class="pl-c"><span class="pl-c">--</span> OR --</span>
<span class="pl-k">SELECT</span> <span class="pl-c1">COUNT</span>(<span class="pl-c1">1</span>) <span class="pl-k">FROM</span> (<span class="pl-k">SELECT DISTINCT</span> memid <span class="pl-k">FROM</span> bookings) <span class="pl-k">AS</span> _</pre></div>
<div class="highlight highlight-source-python"><pre>query <span class="pl-k">=</span> Booking.select(fn.COUNT(Booking.member.distinct()))

<span class="pl-c"><span class="pl-c">#</span> OR:</span>
query <span class="pl-k">=</span> Booking.select(Booking.member).distinct()
count <span class="pl-k">=</span> query.count()  <span class="pl-c"><span class="pl-c">#</span> count() wraps in SELECT COUNT(1) FROM (...)</span></pre></div>
<a name="user-content-list-facilities-with-more-than-1000-slots-booked"></a>
<h3><a id="user-content-list-facilities-with-more-than-1000-slots-booked" class="anchor" aria-hidden="true" href="#list-facilities-with-more-than-1000-slots-booked"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>List facilities with more than 1000 slots booked</h3>
<p>Produce a list of facilities with more than 1000 slots booked. Produce an
output table consisting of facility id and hours, sorted by facility id.</p>
<div class="highlight highlight-source-sql"><pre><span class="pl-k">SELECT</span> facid, <span class="pl-c1">SUM</span>(slots) <span class="pl-k">FROM</span> bookings
<span class="pl-k">GROUP BY</span> facid
<span class="pl-k">HAVING</span> <span class="pl-c1">SUM</span>(slots) <span class="pl-k">&gt;</span> <span class="pl-c1">1000</span>
<span class="pl-k">ORDER BY</span> facid;</pre></div>
<div class="highlight highlight-source-python"><pre>query <span class="pl-k">=</span> (Booking
         .select(Booking.facility, fn.SUM(Booking.slots))
         .group_by(Booking.facility)
         .having(fn.SUM(Booking.slots) <span class="pl-k">&gt;</span> <span class="pl-c1">1000</span>)
         .order_by(Booking.facility))</pre></div>
<a name="user-content-find-the-total-revenue-of-each-facility"></a>
<h3><a id="user-content-find-the-total-revenue-of-each-facility" class="anchor" aria-hidden="true" href="#find-the-total-revenue-of-each-facility"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Find the total revenue of each facility</h3>
<p>Produce a list of facilities along with their total revenue. The output table
should consist of facility name and revenue, sorted by revenue. Remember that
there's a different cost for guests and members!</p>
<div class="highlight highlight-source-sql"><pre><span class="pl-k">SELECT</span> <span class="pl-c1">f</span>.<span class="pl-c1">name</span>, <span class="pl-c1">SUM</span>(<span class="pl-c1">b</span>.<span class="pl-c1">slots</span> <span class="pl-k">*</span> (
CASE WHEN <span class="pl-c1">b</span>.<span class="pl-c1">memid</span> <span class="pl-k">=</span> <span class="pl-c1">0</span> THEN <span class="pl-c1">f</span>.<span class="pl-c1">guestcost</span> ELSE <span class="pl-c1">f</span>.<span class="pl-c1">membercost</span> END)) <span class="pl-k">AS</span> revenue
<span class="pl-k">FROM</span> bookings <span class="pl-k">AS</span> b
<span class="pl-k">INNER JOIN</span> facilities <span class="pl-k">AS</span> f <span class="pl-k">ON</span> <span class="pl-c1">b</span>.<span class="pl-c1">facid</span> <span class="pl-k">=</span> <span class="pl-c1">f</span>.<span class="pl-c1">facid</span>
<span class="pl-k">GROUP BY</span> <span class="pl-c1">f</span>.<span class="pl-c1">name</span>
<span class="pl-k">ORDER BY</span> revenue;</pre></div>
<div class="highlight highlight-source-python"><pre>revenue <span class="pl-k">=</span> fn.SUM(Booking.slots <span class="pl-k">*</span> Case(<span class="pl-c1">None</span>, (
    (Booking.member <span class="pl-k">==</span> <span class="pl-c1">0</span>, Facility.guestcost),
), Facility.membercost))

query <span class="pl-k">=</span> (Facility
         .select(Facility.name, revenue.alias(<span class="pl-s"><span class="pl-pds">'</span>revenue<span class="pl-pds">'</span></span>))
         .join(Booking)
         .group_by(Facility.name)
         .order_by(SQL(<span class="pl-s"><span class="pl-pds">'</span>revenue<span class="pl-pds">'</span></span>)))</pre></div>
<a name="user-content-find-facilities-with-a-total-revenue-less-than-1000"></a>
<h3><a id="user-content-find-facilities-with-a-total-revenue-less-than-1000" class="anchor" aria-hidden="true" href="#find-facilities-with-a-total-revenue-less-than-1000"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Find facilities with a total revenue less than 1000</h3>
<p>Produce a list of facilities with a total revenue less than 1000. Produce an
output table consisting of facility name and revenue, sorted by revenue.
Remember that there's a different cost for guests and members!</p>
<div class="highlight highlight-source-sql"><pre><span class="pl-k">SELECT</span> <span class="pl-c1">f</span>.<span class="pl-c1">name</span>, <span class="pl-c1">SUM</span>(<span class="pl-c1">b</span>.<span class="pl-c1">slots</span> <span class="pl-k">*</span> (
CASE WHEN <span class="pl-c1">b</span>.<span class="pl-c1">memid</span> <span class="pl-k">=</span> <span class="pl-c1">0</span> THEN <span class="pl-c1">f</span>.<span class="pl-c1">guestcost</span> ELSE <span class="pl-c1">f</span>.<span class="pl-c1">membercost</span> END)) <span class="pl-k">AS</span> revenue
<span class="pl-k">FROM</span> bookings <span class="pl-k">AS</span> b
<span class="pl-k">INNER JOIN</span> facilities <span class="pl-k">AS</span> f <span class="pl-k">ON</span> <span class="pl-c1">b</span>.<span class="pl-c1">facid</span> <span class="pl-k">=</span> <span class="pl-c1">f</span>.<span class="pl-c1">facid</span>
<span class="pl-k">GROUP BY</span> <span class="pl-c1">f</span>.<span class="pl-c1">name</span>
<span class="pl-k">HAVING</span> <span class="pl-c1">SUM</span>(<span class="pl-c1">b</span>.<span class="pl-c1">slots</span> <span class="pl-k">*</span> ...) <span class="pl-k">&lt;</span> <span class="pl-c1">1000</span>
<span class="pl-k">ORDER BY</span> revenue;</pre></div>
<div class="highlight highlight-source-python"><pre><span class="pl-c"><span class="pl-c">#</span> Same definition as previous example.</span>
revenue <span class="pl-k">=</span> fn.SUM(Booking.slots <span class="pl-k">*</span> Case(<span class="pl-c1">None</span>, (
    (Booking.member <span class="pl-k">==</span> <span class="pl-c1">0</span>, Facility.guestcost),
), Facility.membercost))

query <span class="pl-k">=</span> (Facility
         .select(Facility.name, revenue.alias(<span class="pl-s"><span class="pl-pds">'</span>revenue<span class="pl-pds">'</span></span>))
         .join(Booking)
         .group_by(Facility.name)
         .having(revenue <span class="pl-k">&lt;</span> <span class="pl-c1">1000</span>)
         .order_by(SQL(<span class="pl-s"><span class="pl-pds">'</span>revenue<span class="pl-pds">'</span></span>)))</pre></div>
<a name="user-content-output-the-facility-id-that-has-the-highest-number-of-slots-booked"></a>
<h3><a id="user-content-output-the-facility-id-that-has-the-highest-number-of-slots-booked" class="anchor" aria-hidden="true" href="#output-the-facility-id-that-has-the-highest-number-of-slots-booked"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Output the facility id that has the highest number of slots booked</h3>
<p>Output the facility id that has the highest number of slots booked.</p>
<div class="highlight highlight-source-sql"><pre><span class="pl-k">SELECT</span> facid, <span class="pl-c1">SUM</span>(slots) <span class="pl-k">FROM</span> bookings
<span class="pl-k">GROUP BY</span> facid
<span class="pl-k">ORDER BY</span> <span class="pl-c1">SUM</span>(slots) <span class="pl-k">DESC</span>
<span class="pl-k">LIMIT</span> <span class="pl-c1">1</span></pre></div>
<div class="highlight highlight-source-python"><pre>query <span class="pl-k">=</span> (Booking
         .select(Booking.facility, fn.SUM(Booking.slots))
         .group_by(Booking.facility)
         .order_by(fn.SUM(Booking.slots).desc())
         .limit(<span class="pl-c1">1</span>))

<span class="pl-c"><span class="pl-c">#</span> Retrieve multiple scalar values by calling scalar() with as_tuple=True.</span>
facid, nslots <span class="pl-k">=</span> query.scalar(<span class="pl-v">as_tuple</span><span class="pl-k">=</span><span class="pl-c1">True</span>)</pre></div>
<a name="user-content-list-the-total-slots-booked-per-facility-per-month-part-2"></a>
<h3><a id="user-content-list-the-total-slots-booked-per-facility-per-month-part-2" class="anchor" aria-hidden="true" href="#list-the-total-slots-booked-per-facility-per-month-part-2"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>List the total slots booked per facility per month, part 2</h3>
<p>Produce a list of the total number of slots booked per facility per month in
the year of 2012. In this version, include output rows containing totals for
all months per facility, and a total for all months for all facilities. The
output table should consist of facility id, month and slots, sorted by the id
and month. When calculating the aggregated values for all months and all
facids, return null values in the month and facid columns.</p>
<p>Postgres ONLY.</p>
<div class="highlight highlight-source-sql"><pre><span class="pl-k">SELECT</span> facid, date_part(<span class="pl-s"><span class="pl-pds">'</span>month<span class="pl-pds">'</span></span>, starttime), <span class="pl-c1">SUM</span>(slots)
<span class="pl-k">FROM</span> booking
<span class="pl-k">WHERE</span> date_part(<span class="pl-s"><span class="pl-pds">'</span>year<span class="pl-pds">'</span></span>, starttime) <span class="pl-k">=</span> <span class="pl-c1">2012</span>
<span class="pl-k">GROUP BY</span> ROLLUP(facid, date_part(<span class="pl-s"><span class="pl-pds">'</span>month<span class="pl-pds">'</span></span>, starttime))
<span class="pl-k">ORDER BY</span> facid, date_part(<span class="pl-s"><span class="pl-pds">'</span>month<span class="pl-pds">'</span></span>, starttime)</pre></div>
<div class="highlight highlight-source-python"><pre>month <span class="pl-k">=</span> fn.date_part(<span class="pl-s"><span class="pl-pds">'</span>month<span class="pl-pds">'</span></span>, Booking.starttime)
query <span class="pl-k">=</span> (Booking
         .select(Booking.facility,
                 month.alias(<span class="pl-s"><span class="pl-pds">'</span>month<span class="pl-pds">'</span></span>),
                 fn.SUM(Booking.slots))
         .where(fn.date_part(<span class="pl-s"><span class="pl-pds">'</span>year<span class="pl-pds">'</span></span>, Booking.starttime) <span class="pl-k">==</span> <span class="pl-c1">2012</span>)
         .group_by(fn.ROLLUP(Booking.facility, month))
         .order_by(Booking.facility, month))</pre></div>
<a name="user-content-list-the-total-hours-booked-per-named-facility"></a>
<h3><a id="user-content-list-the-total-hours-booked-per-named-facility" class="anchor" aria-hidden="true" href="#list-the-total-hours-booked-per-named-facility"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>List the total hours booked per named facility</h3>
<p>Produce a list of the total number of hours booked per facility, remembering
that a slot lasts half an hour. The output table should consist of the
facility id, name, and hours booked, sorted by facility id.</p>
<div class="highlight highlight-source-sql"><pre><span class="pl-k">SELECT</span> <span class="pl-c1">f</span>.<span class="pl-c1">facid</span>, <span class="pl-c1">f</span>.<span class="pl-c1">name</span>, <span class="pl-c1">SUM</span>(<span class="pl-c1">b</span>.<span class="pl-c1">slots</span>) <span class="pl-k">*</span> .<span class="pl-c1">5</span>
<span class="pl-k">FROM</span> facilities <span class="pl-k">AS</span> f
<span class="pl-k">INNER JOIN</span> bookings <span class="pl-k">AS</span> b <span class="pl-k">ON</span> (<span class="pl-c1">f</span>.<span class="pl-c1">facid</span> <span class="pl-k">=</span> <span class="pl-c1">b</span>.<span class="pl-c1">facid</span>)
<span class="pl-k">GROUP BY</span> <span class="pl-c1">f</span>.<span class="pl-c1">facid</span>, <span class="pl-c1">f</span>.<span class="pl-c1">name</span>
<span class="pl-k">ORDER BY</span> <span class="pl-c1">f</span>.<span class="pl-c1">facid</span></pre></div>
<div class="highlight highlight-source-python"><pre>query <span class="pl-k">=</span> (Facility
         .select(Facility.facid, Facility.name, fn.SUM(Booking.slots) <span class="pl-k">*</span> <span class="pl-c1">.5</span>)
         .join(Booking)
         .group_by(Facility.facid, Facility.name)
         .order_by(Facility.facid))</pre></div>
<a name="user-content-list-each-member-s-first-booking-after-september-1st-2012"></a>
<h3><a id="user-content-list-each-members-first-booking-after-september-1st-2012" class="anchor" aria-hidden="true" href="#list-each-members-first-booking-after-september-1st-2012"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>List each member's first booking after September 1st 2012</h3>
<p>Produce a list of each member name, id, and their first booking after
September 1st 2012. Order by member ID.</p>
<div class="highlight highlight-source-sql"><pre><span class="pl-k">SELECT</span> <span class="pl-c1">m</span>.<span class="pl-c1">surname</span>, <span class="pl-c1">m</span>.<span class="pl-c1">firstname</span>, <span class="pl-c1">m</span>.<span class="pl-c1">memid</span>, <span class="pl-c1">min</span>(<span class="pl-c1">b</span>.<span class="pl-c1">starttime</span>) <span class="pl-k">as</span> starttime
<span class="pl-k">FROM</span> members <span class="pl-k">AS</span> m
<span class="pl-k">INNER JOIN</span> bookings <span class="pl-k">AS</span> b <span class="pl-k">ON</span> <span class="pl-c1">b</span>.<span class="pl-c1">memid</span> <span class="pl-k">=</span> <span class="pl-c1">m</span>.<span class="pl-c1">memid</span>
<span class="pl-k">WHERE</span> starttime <span class="pl-k">&gt;=</span> <span class="pl-s"><span class="pl-pds">'</span>2012-09-01<span class="pl-pds">'</span></span>
<span class="pl-k">GROUP BY</span> <span class="pl-c1">m</span>.<span class="pl-c1">surname</span>, <span class="pl-c1">m</span>.<span class="pl-c1">firstname</span>, <span class="pl-c1">m</span>.<span class="pl-c1">memid</span>
<span class="pl-k">ORDER BY</span> <span class="pl-c1">m</span>.<span class="pl-c1">memid</span>;</pre></div>
<div class="highlight highlight-source-python"><pre>query <span class="pl-k">=</span> (Member
         .select(Member.surname, Member.firstname, Member.memid,
                 fn.MIN(Booking.starttime).alias(<span class="pl-s"><span class="pl-pds">'</span>starttime<span class="pl-pds">'</span></span>))
         .join(Booking)
         .where(Booking.starttime <span class="pl-k">&gt;=</span> datetime.date(<span class="pl-c1">2012</span>, <span class="pl-c1">9</span>, <span class="pl-c1">1</span>))
         .group_by(Member.surname, Member.firstname, Member.memid)
         .order_by(Member.memid))</pre></div>
<a name="user-content-produce-a-list-of-member-names-with-each-row-containing-the-total-member-count"></a>
<h3><a id="user-content-produce-a-list-of-member-names-with-each-row-containing-the-total-member-count" class="anchor" aria-hidden="true" href="#produce-a-list-of-member-names-with-each-row-containing-the-total-member-count"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Produce a list of member names, with each row containing the total member count</h3>
<p>Produce a list of member names, with each row containing the total member
count. Order by join date.</p>
<p>Postgres ONLY (as written).</p>
<div class="highlight highlight-source-sql"><pre><span class="pl-k">SELECT</span> <span class="pl-c1">COUNT</span>(<span class="pl-k">*</span>) OVER(), firstname, surname
<span class="pl-k">FROM</span> members <span class="pl-k">ORDER BY</span> joindate</pre></div>
<div class="highlight highlight-source-python"><pre>query <span class="pl-k">=</span> (Member
         .select(fn.COUNT(Member.memid).over(), Member.firstname,
                 Member.surname)
         .order_by(Member.joindate))</pre></div>
<a name="user-content-produce-a-numbered-list-of-members"></a>
<h3><a id="user-content-produce-a-numbered-list-of-members" class="anchor" aria-hidden="true" href="#produce-a-numbered-list-of-members"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Produce a numbered list of members</h3>
<p>Produce a monotonically increasing numbered list of members, ordered by their
date of joining. Remember that member IDs are not guaranteed to be
sequential.</p>
<p>Postgres ONLY (as written).</p>
<div class="highlight highlight-source-sql"><pre><span class="pl-k">SELECT</span> row_number() OVER (<span class="pl-k">ORDER BY</span> joindate), firstname, surname
<span class="pl-k">FROM</span> members <span class="pl-k">ORDER BY</span> joindate;</pre></div>
<div class="highlight highlight-source-python"><pre>query <span class="pl-k">=</span> (Member
         .select(fn.row_number().over(<span class="pl-v">order_by</span><span class="pl-k">=</span>[Member.joindate]),
                 Member.firstname, Member.surname)
         .order_by(Member.joindate))</pre></div>
<a name="user-content-output-the-facility-id-that-has-the-highest-number-of-slots-booked-again"></a>
<h3><a id="user-content-output-the-facility-id-that-has-the-highest-number-of-slots-booked-again" class="anchor" aria-hidden="true" href="#output-the-facility-id-that-has-the-highest-number-of-slots-booked-again"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Output the facility id that has the highest number of slots booked, again</h3>
<p>Output the facility id that has the highest number of slots booked. Ensure
that in the event of a tie, all tieing results get output.</p>
<p>Postgres ONLY (as written).</p>
<div class="highlight highlight-source-sql"><pre><span class="pl-k">SELECT</span> facid, total <span class="pl-k">FROM</span> (
  <span class="pl-k">SELECT</span> facid, <span class="pl-c1">SUM</span>(slots) <span class="pl-k">AS</span> total,
         rank() OVER (<span class="pl-k">order by</span> <span class="pl-c1">SUM</span>(slots) <span class="pl-k">DESC</span>) <span class="pl-k">AS</span> rank
  <span class="pl-k">FROM</span> bookings
  <span class="pl-k">GROUP BY</span> facid
) <span class="pl-k">AS</span> ranked <span class="pl-k">WHERE</span> rank <span class="pl-k">=</span> <span class="pl-c1">1</span></pre></div>
<div class="highlight highlight-source-python"><pre>rank <span class="pl-k">=</span> fn.rank().over(<span class="pl-v">order_by</span><span class="pl-k">=</span>[fn.SUM(Booking.slots).desc()])

subq <span class="pl-k">=</span> (Booking
        .select(Booking.facility, fn.SUM(Booking.slots).alias(<span class="pl-s"><span class="pl-pds">'</span>total<span class="pl-pds">'</span></span>),
                rank.alias(<span class="pl-s"><span class="pl-pds">'</span>rank<span class="pl-pds">'</span></span>))
        .group_by(Booking.facility))

<span class="pl-c"><span class="pl-c">#</span> Here we use a plain Select() to create our query.</span>
query <span class="pl-k">=</span> (Select(<span class="pl-v">columns</span><span class="pl-k">=</span>[subq.c.facid, subq.c.total])
         .from_(subq)
         .where(subq.c.rank <span class="pl-k">==</span> <span class="pl-c1">1</span>)
         .bind(db))  <span class="pl-c"><span class="pl-c">#</span> We must bind() it to the database.</span>

<span class="pl-c"><span class="pl-c">#</span> To iterate over the query results:</span>
<span class="pl-k">for</span> facid, total <span class="pl-k">in</span> query.tuples():
    <span class="pl-c1">print</span>(facid, total)</pre></div>
<a name="user-content-rank-members-by-rounded-hours-used"></a>
<h3><a id="user-content-rank-members-by-rounded-hours-used" class="anchor" aria-hidden="true" href="#rank-members-by-rounded-hours-used"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Rank members by (rounded) hours used</h3>
<p>Produce a list of members, along with the number of hours they've booked in
facilities, rounded to the nearest ten hours. Rank them by this rounded
figure, producing output of first name, surname, rounded hours, rank. Sort by
rank, surname, and first name.</p>
<p>Postgres ONLY (as written).</p>
<div class="highlight highlight-source-sql"><pre><span class="pl-k">SELECT</span> firstname, surname,
((<span class="pl-c1">SUM</span>(<span class="pl-c1">bks</span>.<span class="pl-c1">slots</span>)<span class="pl-k">+</span><span class="pl-c1">10</span>)<span class="pl-k">/</span><span class="pl-c1">20</span>)<span class="pl-k">*</span><span class="pl-c1">10</span> <span class="pl-k">as</span> hours,
rank() over (<span class="pl-k">order by</span> ((<span class="pl-c1">sum</span>(<span class="pl-c1">bks</span>.<span class="pl-c1">slots</span>)<span class="pl-k">+</span><span class="pl-c1">10</span>)<span class="pl-k">/</span><span class="pl-c1">20</span>)<span class="pl-k">*</span><span class="pl-c1">10</span> <span class="pl-k">desc</span>) <span class="pl-k">as</span> rank
<span class="pl-k">FROM</span> members <span class="pl-k">AS</span> mems
<span class="pl-k">INNER JOIN</span> bookings <span class="pl-k">AS</span> bks <span class="pl-k">ON</span> <span class="pl-c1">mems</span>.<span class="pl-c1">memid</span> <span class="pl-k">=</span> <span class="pl-c1">bks</span>.<span class="pl-c1">memid</span>
<span class="pl-k">GROUP BY</span> <span class="pl-c1">mems</span>.<span class="pl-c1">memid</span>
<span class="pl-k">ORDER BY</span> rank, surname, firstname;</pre></div>
<div class="highlight highlight-source-python"><pre>hours <span class="pl-k">=</span> ((fn.SUM(Booking.slots) <span class="pl-k">+</span> <span class="pl-c1">10</span>) <span class="pl-k">/</span> <span class="pl-c1">20</span>) <span class="pl-k">*</span> <span class="pl-c1">10</span>
query <span class="pl-k">=</span> (Member
         .select(Member.firstname, Member.surname, hours.alias(<span class="pl-s"><span class="pl-pds">'</span>hours<span class="pl-pds">'</span></span>),
                 fn.rank().over(<span class="pl-v">order_by</span><span class="pl-k">=</span>[hours.desc()]).alias(<span class="pl-s"><span class="pl-pds">'</span>rank<span class="pl-pds">'</span></span>))
         .join(Booking)
         .group_by(Member.memid)
         .order_by(SQL(<span class="pl-s"><span class="pl-pds">'</span>rank<span class="pl-pds">'</span></span>), Member.surname, Member.firstname))</pre></div>
<a name="user-content-find-the-top-three-revenue-generating-facilities"></a>
<h3><a id="user-content-find-the-top-three-revenue-generating-facilities" class="anchor" aria-hidden="true" href="#find-the-top-three-revenue-generating-facilities"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Find the top three revenue generating facilities</h3>
<p>Produce a list of the top three revenue generating facilities (including
ties). Output facility name and rank, sorted by rank and facility name.</p>
<p>Postgres ONLY (as written).</p>
<div class="highlight highlight-source-sql"><pre><span class="pl-k">SELECT</span> name, rank <span class="pl-k">FROM</span> (
    <span class="pl-k">SELECT</span> <span class="pl-c1">f</span>.<span class="pl-c1">name</span>, RANK() OVER (<span class="pl-k">ORDER BY</span> <span class="pl-c1">SUM</span>(
        CASE WHEN memid <span class="pl-k">=</span> <span class="pl-c1">0</span> THEN slots <span class="pl-k">*</span> <span class="pl-c1">f</span>.<span class="pl-c1">guestcost</span>
        ELSE slots <span class="pl-k">*</span> <span class="pl-c1">f</span>.<span class="pl-c1">membercost</span> END) <span class="pl-k">DESC</span>) <span class="pl-k">AS</span> rank
    <span class="pl-k">FROM</span> bookings
    <span class="pl-k">INNER JOIN</span> facilities <span class="pl-k">AS</span> f <span class="pl-k">ON</span> <span class="pl-c1">bookings</span>.<span class="pl-c1">facid</span> <span class="pl-k">=</span> <span class="pl-c1">f</span>.<span class="pl-c1">facid</span>
    <span class="pl-k">GROUP BY</span> <span class="pl-c1">f</span>.<span class="pl-c1">name</span>) <span class="pl-k">AS</span> subq
<span class="pl-k">WHERE</span> rank <span class="pl-k">&lt;=</span> <span class="pl-c1">3</span>
<span class="pl-k">ORDER BY</span> rank;</pre></div>
<div class="highlight highlight-source-python"><pre>total_cost <span class="pl-k">=</span> fn.SUM(Case(<span class="pl-c1">None</span>, (
    (Booking.member <span class="pl-k">==</span> <span class="pl-c1">0</span>, Booking.slots <span class="pl-k">*</span> Facility.guestcost),
), (Booking.slots <span class="pl-k">*</span> Facility.membercost)))

subq <span class="pl-k">=</span> (Facility
        .select(Facility.name,
                fn.RANK().over(<span class="pl-v">order_by</span><span class="pl-k">=</span>[total_cost.desc()]).alias(<span class="pl-s"><span class="pl-pds">'</span>rank<span class="pl-pds">'</span></span>))
        .join(Booking)
        .group_by(Facility.name))

query <span class="pl-k">=</span> (Select(<span class="pl-v">columns</span><span class="pl-k">=</span>[subq.c.name, subq.c.rank])
         .from_(subq)
         .where(subq.c.rank <span class="pl-k">&lt;=</span> <span class="pl-c1">3</span>)
         .order_by(subq.c.rank)
         .bind(db))  <span class="pl-c"><span class="pl-c">#</span> Here again we used plain Select, and call bind().</span></pre></div>
<a name="user-content-classify-facilities-by-value"></a>
<h3><a id="user-content-classify-facilities-by-value" class="anchor" aria-hidden="true" href="#classify-facilities-by-value"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Classify facilities by value</h3>
<p>Classify facilities into equally sized groups of high, average, and low based
on their revenue. Order by classification and facility name.</p>
<p>Postgres ONLY (as written).</p>
<div class="highlight highlight-source-sql"><pre><span class="pl-k">SELECT</span> name,
  CASE class WHEN <span class="pl-c1">1</span> THEN <span class="pl-s"><span class="pl-pds">'</span>high<span class="pl-pds">'</span></span> WHEN <span class="pl-c1">2</span> THEN <span class="pl-s"><span class="pl-pds">'</span>average<span class="pl-pds">'</span></span> ELSE <span class="pl-s"><span class="pl-pds">'</span>low<span class="pl-pds">'</span></span> END
<span class="pl-k">FROM</span> (
  <span class="pl-k">SELECT</span> <span class="pl-c1">f</span>.<span class="pl-c1">name</span>, ntile(<span class="pl-c1">3</span>) OVER (<span class="pl-k">ORDER BY</span> <span class="pl-c1">SUM</span>(
    CASE WHEN memid <span class="pl-k">=</span> <span class="pl-c1">0</span> THEN slots <span class="pl-k">*</span> <span class="pl-c1">f</span>.<span class="pl-c1">guestcost</span> ELSE slots <span class="pl-k">*</span> <span class="pl-c1">f</span>.<span class="pl-c1">membercost</span>
    END) <span class="pl-k">DESC</span>) <span class="pl-k">AS</span> class
  <span class="pl-k">FROM</span> bookings <span class="pl-k">INNER JOIN</span> facilities <span class="pl-k">AS</span> f <span class="pl-k">ON</span> <span class="pl-c1">bookings</span>.<span class="pl-c1">facid</span> <span class="pl-k">=</span> <span class="pl-c1">f</span>.<span class="pl-c1">facid</span>
  <span class="pl-k">GROUP BY</span> <span class="pl-c1">f</span>.<span class="pl-c1">name</span>
) <span class="pl-k">AS</span> subq
<span class="pl-k">ORDER BY</span> class, name;</pre></div>
<div class="highlight highlight-source-python"><pre>cost <span class="pl-k">=</span> fn.SUM(Case(<span class="pl-c1">None</span>, (
    (Booking.member <span class="pl-k">==</span> <span class="pl-c1">0</span>, Booking.slots <span class="pl-k">*</span> Facility.guestcost),
), (Booking.slots <span class="pl-k">*</span> Facility.membercost)))
subq <span class="pl-k">=</span> (Facility
        .select(Facility.name,
                fn.NTILE(<span class="pl-c1">3</span>).over(<span class="pl-v">order_by</span><span class="pl-k">=</span>[cost.desc()]).alias(<span class="pl-s"><span class="pl-pds">'</span>klass<span class="pl-pds">'</span></span>))
        .join(Booking)
        .group_by(Facility.name))

klass_case <span class="pl-k">=</span> Case(subq.c.klass, [(<span class="pl-c1">1</span>, <span class="pl-s"><span class="pl-pds">'</span>high<span class="pl-pds">'</span></span>), (<span class="pl-c1">2</span>, <span class="pl-s"><span class="pl-pds">'</span>average<span class="pl-pds">'</span></span>)], <span class="pl-s"><span class="pl-pds">'</span>low<span class="pl-pds">'</span></span>)
query <span class="pl-k">=</span> (Select(<span class="pl-v">columns</span><span class="pl-k">=</span>[subq.c.name, klass_case])
         .from_(subq)
         .order_by(subq.c.klass, subq.c.name)
         .bind(db))</pre></div>
<a name="user-content-recursion"></a>
<h2><a id="user-content-recursion" class="anchor" aria-hidden="true" href="#recursion"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Recursion</h2>
<p>Common Table Expressions allow us to, effectively, create our own temporary
tables for the duration of a query - they're largely a convenience to help us
make more readable SQL. Using the WITH RECURSIVE modifier, however, it's
possible for us to create recursive queries. This is enormously advantageous
for working with tree and graph-structured data - imagine retrieving all of the
relations of a graph node to a given depth, for example.</p>
<a name="user-content-find-the-upward-recommendation-chain-for-member-id-27"></a>
<h3><a id="user-content-find-the-upward-recommendation-chain-for-member-id-27" class="anchor" aria-hidden="true" href="#find-the-upward-recommendation-chain-for-member-id-27"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Find the upward recommendation chain for member ID 27</h3>
<p>Find the upward recommendation chain for member ID 27: that is, the member
who recommended them, and the member who recommended that member, and so on.
Return member ID, first name, and surname. Order by descending member id.</p>
<div class="highlight highlight-source-sql"><pre>WITH RECURSIVE recommenders(recommender) <span class="pl-k">as</span> (
  <span class="pl-k">SELECT</span> recommendedby <span class="pl-k">FROM</span> members <span class="pl-k">WHERE</span> memid <span class="pl-k">=</span> <span class="pl-c1">27</span>
  <span class="pl-k">UNION ALL</span>
  <span class="pl-k">SELECT</span> <span class="pl-c1">mems</span>.<span class="pl-c1">recommendedby</span>
  <span class="pl-k">FROM</span> recommenders recs
  <span class="pl-k">INNER JOIN</span> members <span class="pl-k">AS</span> mems <span class="pl-k">ON</span> <span class="pl-c1">mems</span>.<span class="pl-c1">memid</span> <span class="pl-k">=</span> <span class="pl-c1">recs</span>.<span class="pl-c1">recommender</span>
)
<span class="pl-k">SELECT</span> <span class="pl-c1">recs</span>.<span class="pl-c1">recommender</span>, <span class="pl-c1">mems</span>.<span class="pl-c1">firstname</span>, <span class="pl-c1">mems</span>.<span class="pl-c1">surname</span>
<span class="pl-k">FROM</span> recommenders <span class="pl-k">AS</span> recs
<span class="pl-k">INNER JOIN</span> members <span class="pl-k">AS</span> mems <span class="pl-k">ON</span> <span class="pl-c1">recs</span>.<span class="pl-c1">recommender</span> <span class="pl-k">=</span> <span class="pl-c1">mems</span>.<span class="pl-c1">memid</span>
<span class="pl-k">ORDER By</span> memid <span class="pl-k">DESC</span>;</pre></div>
<div class="highlight highlight-source-python"><pre><span class="pl-c"><span class="pl-c">#</span> Base-case of recursive CTE. Get member recommender where memid=27.</span>
base <span class="pl-k">=</span> (Member
        .select(Member.recommendedby)
        .where(Member.memid <span class="pl-k">==</span> <span class="pl-c1">27</span>)
        .cte(<span class="pl-s"><span class="pl-pds">'</span>recommenders<span class="pl-pds">'</span></span>, <span class="pl-v">recursive</span><span class="pl-k">=</span><span class="pl-c1">True</span>, <span class="pl-v">columns</span><span class="pl-k">=</span>(<span class="pl-s"><span class="pl-pds">'</span>recommender<span class="pl-pds">'</span></span>,)))

<span class="pl-c"><span class="pl-c">#</span> Recursive term of CTE. Get recommender of previous recommender.</span>
<span class="pl-c1">MA</span> <span class="pl-k">=</span> Member.alias()
recursive <span class="pl-k">=</span> (<span class="pl-c1">MA</span>
             .select(<span class="pl-c1">MA</span>.recommendedby)
             .join(base, <span class="pl-v">on</span><span class="pl-k">=</span>(<span class="pl-c1">MA</span>.memid <span class="pl-k">==</span> base.c.recommender)))

<span class="pl-c"><span class="pl-c">#</span> Combine the base-case with the recursive term.</span>
cte <span class="pl-k">=</span> base.union_all(recursive)

<span class="pl-c"><span class="pl-c">#</span> Select from the recursive CTE, joining on member to get name info.</span>
query <span class="pl-k">=</span> (cte
         .select_from(cte.c.recommender, Member.firstname, Member.surname)
         .join(Member, <span class="pl-v">on</span><span class="pl-k">=</span>(cte.c.recommender <span class="pl-k">==</span> Member.memid))
         .order_by(Member.memid.desc()))</pre></div>

</article>
  </div>

    </div>

  

  <details class="details-reset details-overlay details-overlay-dark">
    <summary data-hotkey="l" aria-label="Jump to line"></summary>
    <details-dialog class="Box Box--overlay d-flex flex-column anim-fade-in fast linejump" aria-label="Jump to line">
      <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="js-jump-to-line-form Box-body d-flex" action="" accept-charset="UTF-8" method="get"><input name="utf8" type="hidden" value="&#x2713;" />
        <input class="form-control flex-auto mr-3 linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line&hellip;" aria-label="Jump to line" autofocus>
        <button type="submit" class="btn" data-close-dialog>Go</button>
</form>    </details-dialog>
  </details>



  </div>
</div>

    </main>
  </div>
  

  </div>

        
<div class="footer container-lg width-full p-responsive" role="contentinfo">
  <div class="position-relative d-flex flex-row-reverse flex-lg-row flex-wrap flex-lg-nowrap flex-justify-center flex-lg-justify-between pt-6 pb-2 mt-6 f6 text-gray border-top border-gray-light ">
    <ul class="list-style-none d-flex flex-wrap col-12 col-lg-5 flex-justify-center flex-lg-justify-between mb-2 mb-lg-0">
      <li class="mr-3 mr-lg-0">&copy; 2019 <span title="0.17176s from unicorn-6748555dd4-sxpk4">GitHub</span>, Inc.</li>
        <li class="mr-3 mr-lg-0"><a data-ga-click="Footer, go to terms, text:terms" href="https://github.com/site/terms">Terms</a></li>
        <li class="mr-3 mr-lg-0"><a data-ga-click="Footer, go to privacy, text:privacy" href="https://github.com/site/privacy">Privacy</a></li>
        <li class="mr-3 mr-lg-0"><a data-ga-click="Footer, go to security, text:security" href="https://github.com/security">Security</a></li>
        <li class="mr-3 mr-lg-0"><a href="https://githubstatus.com/" data-ga-click="Footer, go to status, text:status">Status</a></li>
        <li><a data-ga-click="Footer, go to help, text:help" href="https://help.github.com">Help</a></li>
    </ul>

    <a aria-label="Homepage" title="GitHub" class="footer-octicon d-none d-lg-block mx-lg-4" href="https://github.com">
      <svg height="24" class="octicon octicon-mark-github" viewBox="0 0 16 16" version="1.1" width="24" aria-hidden="true"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"/></svg>
</a>
   <ul class="list-style-none d-flex flex-wrap col-12 col-lg-5 flex-justify-center flex-lg-justify-between mb-2 mb-lg-0">
        <li class="mr-3 mr-lg-0"><a data-ga-click="Footer, go to contact, text:contact" href="https://github.com/contact">Contact GitHub</a></li>
        <li class="mr-3 mr-lg-0"><a href="https://github.com/pricing" data-ga-click="Footer, go to Pricing, text:Pricing">Pricing</a></li>
      <li class="mr-3 mr-lg-0"><a href="https://developer.github.com" data-ga-click="Footer, go to api, text:api">API</a></li>
      <li class="mr-3 mr-lg-0"><a href="https://training.github.com" data-ga-click="Footer, go to training, text:training">Training</a></li>
        <li class="mr-3 mr-lg-0"><a href="https://github.blog" data-ga-click="Footer, go to blog, text:blog">Blog</a></li>
        <li><a data-ga-click="Footer, go to about, text:about" href="https://github.com/about">About</a></li>

    </ul>
  </div>
  <div class="d-flex flex-justify-center pb-6">
    <span class="f6 text-gray-light"></span>
  </div>
</div>



  <div id="ajax-error-message" class="ajax-error-message flash flash-error">
    <svg class="octicon octicon-alert" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.893 1.5c-.183-.31-.52-.5-.887-.5s-.703.19-.886.5L.138 13.499a.98.98 0 0 0 0 1.001c.193.31.53.501.886.501h13.964c.367 0 .704-.19.877-.5a1.03 1.03 0 0 0 .01-1.002L8.893 1.5zm.133 11.497H6.987v-2.003h2.039v2.003zm0-3.004H6.987V5.987h2.039v4.006z"/></svg>
    <button type="button" class="flash-close js-ajax-error-dismiss" aria-label="Dismiss error">
      <svg class="octicon octicon-x" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"/></svg>
    </button>
    You can’t perform that action at this time.
  </div>


    <script crossorigin="anonymous" integrity="sha512-RwS+8T0XPR5cCcBdDmGcf/cL+FfKUdIjfRL93fvzAzjVUdgaknI2UpShICXEAx0szS45xu9lpIDeacN+3d3hZw==" type="application/javascript" src="https://github.githubassets.com/assets/compat-bootstrap-94789d4c.js"></script>
    <script crossorigin="anonymous" integrity="sha512-zkplp60DvoRCC9CXX7c0VMvowqQVA30d13E4xweoE5aCO1wqyvOEzSkt7aoeDqZ1sdAIPM00n8r79qznbDdfBQ==" type="application/javascript" src="https://github.githubassets.com/assets/frameworks-c254eb02.js"></script>
    
    <script crossorigin="anonymous" async="async" integrity="sha512-Dbw4uiqkZzIeYFoVEEjeHAXpusff00Ir82f5wmO3/jHs+dact1lLsiJTYEbhDwsd63tWWgj9vPFxxr01nd8BPA==" type="application/javascript" src="https://github.githubassets.com/assets/github-bootstrap-67222ece.js"></script>
    
    
    
  <div class="js-stale-session-flash stale-session-flash flash flash-warn flash-banner" hidden
    >
    <svg class="octicon octicon-alert" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.893 1.5c-.183-.31-.52-.5-.887-.5s-.703.19-.886.5L.138 13.499a.98.98 0 0 0 0 1.001c.193.31.53.501.886.501h13.964c.367 0 .704-.19.877-.5a1.03 1.03 0 0 0 .01-1.002L8.893 1.5zm.133 11.497H6.987v-2.003h2.039v2.003zm0-3.004H6.987V5.987h2.039v4.006z"/></svg>
    <span class="signed-in-tab-flash">You signed in with another tab or window. <a href="">Reload</a> to refresh your session.</span>
    <span class="signed-out-tab-flash">You signed out in another tab or window. <a href="">Reload</a> to refresh your session.</span>
  </div>
  <template id="site-details-dialog">
  <details class="details-reset details-overlay details-overlay-dark lh-default text-gray-dark hx_rsm" open>
    <summary role="button" aria-label="Close dialog"></summary>
    <details-dialog class="Box Box--overlay d-flex flex-column anim-fade-in fast hx_rsm-dialog hx_rsm-modal">
      <button class="Box-btn-octicon m-0 btn-octicon position-absolute right-0 top-0" type="button" aria-label="Close dialog" data-close-dialog>
        <svg class="octicon octicon-x" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"/></svg>
      </button>
      <div class="octocat-spinner my-6 js-details-dialog-spinner"></div>
    </details-dialog>
  </details>
</template>

  <div class="Popover js-hovercard-content position-absolute" style="display: none; outline: none;" tabindex="0">
  <div class="Popover-message Popover-message--bottom-left Popover-message--large Box box-shadow-large" style="width:360px;">
  </div>
</div>

  <div aria-live="polite" class="js-global-screen-reader-notice sr-only"></div>

  </body>
</html>

