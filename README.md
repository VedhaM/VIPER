





<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
  <link rel="dns-prefetch" href="https://assets-cdn.github.com">
  <link rel="dns-prefetch" href="https://avatars0.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars1.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars2.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars3.githubusercontent.com">
  <link rel="dns-prefetch" href="https://github-cloud.s3.amazonaws.com">
  <link rel="dns-prefetch" href="https://user-images.githubusercontent.com/">



  <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/frameworks-77c3b874f32e71b14cded5a120f42f5c7288fa52e0a37f2d5919fbd8bcfca63c.css" integrity="sha256-d8O4dPMucbFM3tWhIPQvXHKI+lLgo38tWRn72Lz8pjw=" media="all" rel="stylesheet" />
  <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/github-3217809f92ad8d74c7d2209d88027e064a99a8ced3313cf969ec601dd3217769.css" integrity="sha256-MheAn5KtjXTH0iCdiAJ+BkqZqM7TMTz5aexgHdMhd2k=" media="all" rel="stylesheet" />
  
  
  
  

  <meta name="viewport" content="width=device-width">
  
  <title>fantastic-ios-architecture/README.md at master · onmyway133/fantastic-ios-architecture</title>
  <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">
  <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
  <meta property="fb:app_id" content="1401488693436528">

    
    <meta content="https://avatars0.githubusercontent.com/u/2284279?v=4&amp;s=400" property="og:image" /><meta content="GitHub" property="og:site_name" /><meta content="object" property="og:type" /><meta content="onmyway133/fantastic-ios-architecture" property="og:title" /><meta content="https://github.com/onmyway133/fantastic-ios-architecture" property="og:url" /><meta content="fantastic-ios-architecture - :japanese_castle: Better ways to structure iOS apps" property="og:description" />

  <link rel="assets" href="https://assets-cdn.github.com/">
  <link rel="web-socket" href="wss://live.github.com/_sockets/VjI6MTk5NjE1ODUyOmFmNzkyNGIzMjIyZDc0MWFjYzkxNDAzZWJkNzg3YTc0NzI2MzM0NjM0NDAzN2ExYTE1OWYxN2U3MzMxMzZhYzc=--9f1d9350315f983cc541fd58575590297ee866dc">
  <meta name="pjax-timeout" content="1000">
  <link rel="sudo-modal" href="/sessions/sudo_modal">
  <meta name="request-id" content="C168:7B32:E6D5F8:1A17917:599CA28A" data-pjax-transient>
  

  <meta name="selected-link" value="repo_source" data-pjax-transient>

  <meta name="google-site-verification" content="KT5gs8h0wvaagLKAVWq8bbeNwnZZK1r1XQysX3xurLU">
<meta name="google-site-verification" content="ZzhVyEFwb7w3e0-uOTltm8Jsck2F5StVihD0exw2fsA">
    <meta name="google-analytics" content="UA-3769691-2">

<meta content="collector.githubapp.com" name="octolytics-host" /><meta content="github" name="octolytics-app-id" /><meta content="https://collector.githubapp.com/github-external/browser_event" name="octolytics-event-url" /><meta content="C168:7B32:E6D5F8:1A17917:599CA28A" name="octolytics-dimension-request_id" /><meta content="iad" name="octolytics-dimension-region_edge" /><meta content="iad" name="octolytics-dimension-region_render" /><meta content="31258768" name="octolytics-actor-id" /><meta content="VedhaM" name="octolytics-actor-login" /><meta content="d926663f8a47b1c3dda54c70d54ca314ffb3b52eeb4818e4b06711ff749fe5ec" name="octolytics-actor-hash" />
<meta content="/&lt;user-name&gt;/&lt;repo-name&gt;/blob/show" data-pjax-transient="true" name="analytics-location" />




  <meta class="js-ga-set" name="dimension1" content="Logged In">


  

      <meta name="hostname" content="github.com">
  <meta name="user-login" content="VedhaM">

      <meta name="expected-hostname" content="github.com">
    <meta name="js-proxy-site-detection-payload" content="NmM5Yjk0ZmQ2NThhZjdjYzE4ZjE3ZWU1Mjk2NzhiYjQ2OTAwNGM0MzAyOWNmNzU0NWMyYmZiNjZhY2JhNTQyZHx7InJlbW90ZV9hZGRyZXNzIjoiMTk5LjY0LjcuNTgiLCJyZXF1ZXN0X2lkIjoiQzE2ODo3QjMyOkU2RDVGODoxQTE3OTE3OjU5OUNBMjhBIiwidGltZXN0YW1wIjoxNTAzNDM3NDUwLCJob3N0IjoiZ2l0aHViLmNvbSJ9">

    <meta name="enabled-features" content="UNIVERSE_BANNER">

  <meta name="html-safe-nonce" content="c77cc77df612f0253442fdb039f221deb4021be7">

  <meta http-equiv="x-pjax-version" content="e351ad121e63a404782875f3f2c81cb1">
  

      <link href="https://github.com/onmyway133/fantastic-ios-architecture/commits/master.atom" rel="alternate" title="Recent Commits to fantastic-ios-architecture:master" type="application/atom+xml">

  <meta name="description" content="fantastic-ios-architecture - :japanese_castle: Better ways to structure iOS apps">
  <meta name="go-import" content="github.com/onmyway133/fantastic-ios-architecture git https://github.com/onmyway133/fantastic-ios-architecture.git">

  <meta content="2284279" name="octolytics-dimension-user_id" /><meta content="onmyway133" name="octolytics-dimension-user_login" /><meta content="49082519" name="octolytics-dimension-repository_id" /><meta content="onmyway133/fantastic-ios-architecture" name="octolytics-dimension-repository_nwo" /><meta content="true" name="octolytics-dimension-repository_public" /><meta content="false" name="octolytics-dimension-repository_is_fork" /><meta content="49082519" name="octolytics-dimension-repository_network_root_id" /><meta content="onmyway133/fantastic-ios-architecture" name="octolytics-dimension-repository_network_root_nwo" /><meta content="false" name="octolytics-dimension-repository_explore_github_marketplace_ci_cta_shown" />


    <link rel="canonical" href="https://github.com/onmyway133/fantastic-ios-architecture/blob/master/README.md" data-pjax-transient>


  <meta name="browser-stats-url" content="https://api.github.com/_private/browser/stats">

  <meta name="browser-errors-url" content="https://api.github.com/_private/browser/errors">

  <link rel="mask-icon" href="https://assets-cdn.github.com/pinned-octocat.svg" color="#000000">
  <link rel="icon" type="image/x-icon" href="https://assets-cdn.github.com/favicon.ico">

<meta name="theme-color" content="#1e2327">


  <meta name="u2f-support" content="true">

  </head>

  <body class="logged-in env-production page-blob">
    

  <div class="position-relative js-header-wrapper ">
    <a href="#start-of-content" tabindex="1" class="bg-black text-white p-3 show-on-focus js-skip-to-content">Skip to content</a>
    <div id="js-pjax-loader-bar" class="pjax-loader-bar"><div class="progress"></div></div>

    
    
    



        
<header class="Header  f5" role="banner">
  <div class="d-flex px-3 flex-justify-between container-lg">
    <div class="d-flex flex-justify-between">
      <a class="header-logo-invertocat" href="https://github.com/" data-hotkey="g d" aria-label="Homepage" data-ga-click="Header, go to dashboard, icon:logo">
  <svg aria-hidden="true" class="octicon octicon-mark-github" height="32" version="1.1" viewBox="0 0 16 16" width="32"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"/></svg>
</a>


    </div>

    <div class="HeaderMenu d-flex flex-justify-between flex-auto">
      <div class="d-flex">
            <div class="">
              <div class="header-search scoped-search site-scoped-search js-site-search" role="search">
  <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/onmyway133/fantastic-ios-architecture/search" class="js-site-search-form" data-scoped-search-url="/onmyway133/fantastic-ios-architecture/search" data-unscoped-search-url="/search" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
    <label class="form-control header-search-wrapper js-chromeless-input-container">
        <a href="/onmyway133/fantastic-ios-architecture/blob/master/README.md" class="header-search-scope no-underline">This repository</a>
      <input type="text"
        class="form-control header-search-input js-site-search-focus js-site-search-field is-clearable"
        data-hotkey="s"
        name="q"
        value=""
        placeholder="Search"
        aria-label="Search this repository"
        data-unscoped-placeholder="Search GitHub"
        data-scoped-placeholder="Search"
        autocapitalize="off">
        <input type="hidden" class="js-site-search-type-field" name="type" >
    </label>
</form></div>

            </div>

          <ul class="d-flex pl-2 flex-items-center text-bold list-style-none" role="navigation">
            <li>
              <a href="/pulls" aria-label="Pull requests you created" class="js-selected-navigation-item HeaderNavlink px-2" data-ga-click="Header, click, Nav menu - item:pulls context:user" data-hotkey="g p" data-selected-links="/pulls /pulls/assigned /pulls/mentioned /pulls">
                Pull requests
</a>            </li>
            <li>
              <a href="/issues" aria-label="Issues you created" class="js-selected-navigation-item HeaderNavlink px-2" data-ga-click="Header, click, Nav menu - item:issues context:user" data-hotkey="g i" data-selected-links="/issues /issues/assigned /issues/mentioned /issues">
                Issues
</a>            </li>
                <li>
                  <a href="/marketplace" class="js-selected-navigation-item HeaderNavlink px-2" data-ga-click="Header, click, Nav menu - item:marketplace context:user" data-selected-links=" /marketplace">
                    Marketplace
</a>                </li>
            <li>
              <a href="/explore" class="js-selected-navigation-item HeaderNavlink px-2" data-ga-click="Header, click, Nav menu - item:explore" data-selected-links="/explore /trending /trending/developers /integrations /integrations/feature/code /integrations/feature/collaborate /integrations/feature/ship showcases showcases_search showcases_landing /explore">
                Explore
</a>            </li>
          </ul>
      </div>

      <div class="d-flex">
        
<ul class="user-nav d-flex flex-items-center list-style-none" id="user-links">
  <li>
    <span class="">
      

    </span>
  </li>

  <li class="dropdown js-menu-container">
    <a class="HeaderNavlink tooltipped tooltipped-s js-menu-target d-flex px-2 flex-items-center" href="/new"
       aria-label="Create new…"
       aria-expanded="false"
       aria-haspopup="true"
       data-ga-click="Header, create new, icon:add">
      <svg aria-hidden="true" class="octicon octicon-plus float-left" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 9H7v5H5V9H0V7h5V2h2v5h5z"/></svg>
      <span class="dropdown-caret mt-1"></span>
    </a>

    <div class="dropdown-menu-content js-menu-content">
      <ul class="dropdown-menu dropdown-menu-sw">
        
<a class="dropdown-item" href="/new" data-ga-click="Header, create new repository">
  New repository
</a>

  <a class="dropdown-item" href="/new/import" data-ga-click="Header, import a repository">
    Import repository
  </a>

<a class="dropdown-item" href="https://gist.github.com/" data-ga-click="Header, create new gist">
  New gist
</a>

  <a class="dropdown-item" href="/organizations/new" data-ga-click="Header, create new organization">
    New organization
  </a>



  <div class="dropdown-divider"></div>
  <div class="dropdown-header">
    <span title="onmyway133/fantastic-ios-architecture">This repository</span>
  </div>
    <a class="dropdown-item" href="/onmyway133/fantastic-ios-architecture/issues/new" data-ga-click="Header, create new issue">
      New issue
    </a>

      </ul>
    </div>
  </li>

  <li class="dropdown js-menu-container">

    <a class="HeaderNavlink name tooltipped tooltipped-sw js-menu-target d-flex pl-2 flex-items-center" href="/VedhaM"
       aria-label="View profile and more"
       aria-expanded="false"
       aria-haspopup="true"
       data-ga-click="Header, show menu, icon:avatar">
      <img alt="@VedhaM" class="avatar" src="https://avatars2.githubusercontent.com/u/31258768?v=4&amp;s=40" height="20" width="20">
      <span class="dropdown-caret mt-1"></span>
    </a>

    <div class="dropdown-menu-content js-menu-content">
      <div class="dropdown-menu dropdown-menu-sw">
        <div class="dropdown-header header-nav-current-user css-truncate">
          Signed in as <strong class="css-truncate-target">VedhaM</strong>
        </div>

        <div class="dropdown-divider"></div>

        <a class="dropdown-item" href="/VedhaM" data-ga-click="Header, go to profile, text:your profile">
          Your profile
        </a>
        <a class="dropdown-item" href="/VedhaM?tab=stars" data-ga-click="Header, go to starred repos, text:your stars">
          Your stars
        </a>
          <a class="dropdown-item" href="https://gist.github.com/" data-ga-click="Header, your gists, text:your gists">Your Gists</a>

        <div class="dropdown-divider"></div>

        <a class="dropdown-item" href="https://help.github.com" data-ga-click="Header, go to help, text:help">
          Help
        </a>

        <a class="dropdown-item" href="/settings/profile" data-ga-click="Header, go to settings, icon:settings">
          Settings
        </a>

        <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/logout" class="logout-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="A+ccd08AwtNb0HLIWSIRaJ51dICQ9thJ05rTg1VqdTtt/3VR2S4J0U5xmgKc0zI2K8tMMBcALWqdv0uLfyu6LA==" /></div>
          <button type="submit" class="dropdown-item dropdown-signout" data-ga-click="Header, sign out, icon:logout">
            Sign out
          </button>
</form>      </div>
    </div>
  </li>
</ul>


        <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/logout" class="sr-only right-0" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="5umjosR+TVGWKiotSfHPdEZy7pso+5fP5moCUPVFypWI8cqEUlCGU4OLwueMAOwq88zWK68NYuyoT5pY3wQFgg==" /></div>
          <button type="submit" class="dropdown-item dropdown-signout" data-ga-click="Header, sign out, icon:logout">
            Sign out
          </button>
</form>      </div>
    </div>
  </div>
</header>


      

  </div>

  <div id="start-of-content" class="show-on-focus"></div>

    <div id="js-flash-container">
</div>



  <div role="main">
        <div itemscope itemtype="http://schema.org/SoftwareSourceCode">
    <div id="js-repo-pjax-container" data-pjax-container>
      





    <div class="pagehead repohead instapaper_ignore readability-menu experiment-repo-nav">
      <div class="container repohead-details-container">

        <ul class="pagehead-actions">
  <li>
        <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/notifications/subscribe" class="js-social-container" data-autosubmit="true" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="GWkxgYF3MrRB0RtTnRRcIaWedULnW2Kilw3Iqt+d2ZDnPLbopbmo7gHpu80S1t49o9ZCRrorXBiTS3E16GX6rQ==" /></div>      <input class="form-control" id="repository_id" name="repository_id" type="hidden" value="49082519" />

        <div class="select-menu js-menu-container js-select-menu">
          <a href="/onmyway133/fantastic-ios-architecture/subscription"
            class="btn btn-sm btn-with-count select-menu-button js-menu-target"
            role="button"
            aria-haspopup="true"
            aria-expanded="false"
            aria-label="Toggle repository notifications menu"
            data-ga-click="Repository, click Watch settings, action:blob#show">
            <span class="js-select-button">
                <svg aria-hidden="true" class="octicon octicon-eye" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
                Watch
            </span>
          </a>
            <a class="social-count js-social-count"
              href="/onmyway133/fantastic-ios-architecture/watchers"
              aria-label="98 users are watching this repository">
              98
            </a>

        <div class="select-menu-modal-holder">
          <div class="select-menu-modal subscription-menu-modal js-menu-content">
            <div class="select-menu-header js-navigation-enable" tabindex="-1">
              <svg aria-label="Close" class="octicon octicon-x js-menu-close" height="16" role="img" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48z"/></svg>
              <span class="select-menu-title">Notifications</span>
            </div>

              <div class="select-menu-list js-navigation-container" role="menu">

                <div class="select-menu-item js-navigation-item selected" role="menuitem" tabindex="0">
                  <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
                  <div class="select-menu-item-text">
                    <input checked="checked" id="do_included" name="do" type="radio" value="included" />
                    <span class="select-menu-item-heading">Not watching</span>
                    <span class="description">Be notified when participating or @mentioned.</span>
                    <span class="js-select-button-text hidden-select-button-text">
                      <svg aria-hidden="true" class="octicon octicon-eye" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
                      Watch
                    </span>
                  </div>
                </div>

                <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                  <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
                  <div class="select-menu-item-text">
                    <input id="do_subscribed" name="do" type="radio" value="subscribed" />
                    <span class="select-menu-item-heading">Watching</span>
                    <span class="description">Be notified of all conversations.</span>
                    <span class="js-select-button-text hidden-select-button-text">
                      <svg aria-hidden="true" class="octicon octicon-eye" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
                        Unwatch
                    </span>
                  </div>
                </div>

                <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                  <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
                  <div class="select-menu-item-text">
                    <input id="do_ignore" name="do" type="radio" value="ignore" />
                    <span class="select-menu-item-heading">Ignoring</span>
                    <span class="description">Never be notified.</span>
                    <span class="js-select-button-text hidden-select-button-text">
                      <svg aria-hidden="true" class="octicon octicon-mute" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M8 2.81v10.38c0 .67-.81 1-1.28.53L3 10H1c-.55 0-1-.45-1-1V7c0-.55.45-1 1-1h2l3.72-3.72C7.19 1.81 8 2.14 8 2.81zm7.53 3.22l-1.06-1.06-1.97 1.97-1.97-1.97-1.06 1.06L11.44 8 9.47 9.97l1.06 1.06 1.97-1.97 1.97 1.97 1.06-1.06L13.56 8l1.97-1.97z"/></svg>
                        Stop ignoring
                    </span>
                  </div>
                </div>

              </div>

            </div>
          </div>
        </div>
</form>
  </li>

  <li>
    
  <div class="js-toggler-container js-social-container starring-container ">
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/onmyway133/fantastic-ios-architecture/unstar" class="starred" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="xnYtS095FHcfjqfLYNDVtmh6QkjumJpk6rq3LvQ+GTTZtIbSll+rYPQO7L1aasNOjURpkAw76VH171H6DhVRCw==" /></div>
      <button
        type="submit"
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Unstar this repository" title="Unstar onmyway133/fantastic-ios-architecture"
        data-ga-click="Repository, click unstar button, action:blob#show; text:Unstar">
        <svg aria-hidden="true" class="octicon octicon-star" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M14 6l-4.9-.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14 7 11.67 11.33 14l-.93-4.74z"/></svg>
        Unstar
      </button>
        <a class="social-count js-social-count" href="/onmyway133/fantastic-ios-architecture/stargazers"
           aria-label="1182 users starred this repository">
          1,182
        </a>
</form>
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/onmyway133/fantastic-ios-architecture/star" class="unstarred" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="X4DslPJ+0V3d2T8wqfh5ozj3elR0wL+JXRX77TuFccMhOSMQhECJ1pe5Lbec3Zzn4n4JijYtu+Eo45WEsBnTog==" /></div>
      <button
        type="submit"
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Star this repository" title="Star onmyway133/fantastic-ios-architecture"
        data-ga-click="Repository, click star button, action:blob#show; text:Star">
        <svg aria-hidden="true" class="octicon octicon-star" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M14 6l-4.9-.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14 7 11.67 11.33 14l-.93-4.74z"/></svg>
        Star
      </button>
        <a class="social-count js-social-count" href="/onmyway133/fantastic-ios-architecture/stargazers"
           aria-label="1182 users starred this repository">
          1,182
        </a>
</form>  </div>

  </li>

  <li>
          <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/onmyway133/fantastic-ios-architecture/fork" class="btn-with-count" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="MN+ZnEQTLB9szdNWRghxMzjNfeqPkBx5rIc1AeXCc9BF/Z/AhhaAyWute2eUgBlsLbmyH6IGiCsk2tJK212REg==" /></div>
            <button
                type="submit"
                class="btn btn-sm btn-with-count"
                data-ga-click="Repository, show fork modal, action:blob#show; text:Fork"
                title="Fork your own copy of onmyway133/fantastic-ios-architecture to your account"
                aria-label="Fork your own copy of onmyway133/fantastic-ios-architecture to your account">
              <svg aria-hidden="true" class="octicon octicon-repo-forked" height="16" version="1.1" viewBox="0 0 10 16" width="10"><path fill-rule="evenodd" d="M8 1a1.993 1.993 0 0 0-1 3.72V6L5 8 3 6V4.72A1.993 1.993 0 0 0 2 1a1.993 1.993 0 0 0-1 3.72V6.5l3 3v1.78A1.993 1.993 0 0 0 5 15a1.993 1.993 0 0 0 1-3.72V9.5l3-3V4.72A1.993 1.993 0 0 0 8 1zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3 10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3-10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"/></svg>
              Fork
            </button>
</form>
    <a href="/onmyway133/fantastic-ios-architecture/network" class="social-count"
       aria-label="112 users forked this repository">
      112
    </a>
  </li>
</ul>

        <h1 class="public ">
  <svg aria-hidden="true" class="octicon octicon-repo" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
  <span class="author" itemprop="author"><a href="/onmyway133" class="url fn" rel="author">onmyway133</a></span><!--
--><span class="path-divider">/</span><!--
--><strong itemprop="name"><a href="/onmyway133/fantastic-ios-architecture" data-pjax="#js-repo-pjax-container">fantastic-ios-architecture</a></strong>

</h1>

      </div>
      <div class="container">
        
<nav class="reponav js-repo-nav js-sidenav-container-pjax"
     itemscope
     itemtype="http://schema.org/BreadcrumbList"
     role="navigation"
     data-pjax="#js-repo-pjax-container">

  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a href="/onmyway133/fantastic-ios-architecture" class="js-selected-navigation-item selected reponav-item" data-hotkey="g c" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches /onmyway133/fantastic-ios-architecture" itemprop="url">
      <svg aria-hidden="true" class="octicon octicon-code" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M9.5 3L8 4.5 11.5 8 8 11.5 9.5 13 14 8 9.5 3zm-5 0L0 8l4.5 5L6 11.5 2.5 8 6 4.5 4.5 3z"/></svg>
      <span itemprop="name">Code</span>
      <meta itemprop="position" content="1">
</a>  </span>

    <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
      <a href="/onmyway133/fantastic-ios-architecture/issues" class="js-selected-navigation-item reponav-item" data-hotkey="g i" data-selected-links="repo_issues repo_labels repo_milestones /onmyway133/fantastic-ios-architecture/issues" itemprop="url">
        <svg aria-hidden="true" class="octicon octicon-issue-opened" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M7 2.3c3.14 0 5.7 2.56 5.7 5.7s-2.56 5.7-5.7 5.7A5.71 5.71 0 0 1 1.3 8c0-3.14 2.56-5.7 5.7-5.7zM7 1C3.14 1 0 4.14 0 8s3.14 7 7 7 7-3.14 7-7-3.14-7-7-7zm1 3H6v5h2V4zm0 6H6v2h2v-2z"/></svg>
        <span itemprop="name">Issues</span>
        <span class="Counter">0</span>
        <meta itemprop="position" content="2">
</a>    </span>

  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a href="/onmyway133/fantastic-ios-architecture/pulls" class="js-selected-navigation-item reponav-item" data-hotkey="g p" data-selected-links="repo_pulls /onmyway133/fantastic-ios-architecture/pulls" itemprop="url">
      <svg aria-hidden="true" class="octicon octicon-git-pull-request" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M11 11.28V5c-.03-.78-.34-1.47-.94-2.06C9.46 2.35 8.78 2.03 8 2H7V0L4 3l3 3V4h1c.27.02.48.11.69.31.21.2.3.42.31.69v6.28A1.993 1.993 0 0 0 10 15a1.993 1.993 0 0 0 1-3.72zm-1 2.92c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zM4 3c0-1.11-.89-2-2-2a1.993 1.993 0 0 0-1 3.72v6.56A1.993 1.993 0 0 0 2 15a1.993 1.993 0 0 0 1-3.72V4.72c.59-.34 1-.98 1-1.72zm-.8 10c0 .66-.55 1.2-1.2 1.2-.65 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"/></svg>
      <span itemprop="name">Pull requests</span>
      <span class="Counter">0</span>
      <meta itemprop="position" content="3">
</a>  </span>

    <a href="/onmyway133/fantastic-ios-architecture/projects" class="js-selected-navigation-item reponav-item" data-selected-links="repo_projects new_repo_project repo_project /onmyway133/fantastic-ios-architecture/projects">
      <svg aria-hidden="true" class="octicon octicon-project" height="16" version="1.1" viewBox="0 0 15 16" width="15"><path fill-rule="evenodd" d="M10 12h3V2h-3v10zm-4-2h3V2H6v8zm-4 4h3V2H2v12zm-1 1h13V1H1v14zM14 0H1a1 1 0 0 0-1 1v14a1 1 0 0 0 1 1h13a1 1 0 0 0 1-1V1a1 1 0 0 0-1-1z"/></svg>
      Projects
      <span class="Counter" >0</span>
</a>
    <a href="/onmyway133/fantastic-ios-architecture/wiki" class="js-selected-navigation-item reponav-item" data-hotkey="g w" data-selected-links="repo_wiki /onmyway133/fantastic-ios-architecture/wiki">
      <svg aria-hidden="true" class="octicon octicon-book" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M3 5h4v1H3V5zm0 3h4V7H3v1zm0 2h4V9H3v1zm11-5h-4v1h4V5zm0 2h-4v1h4V7zm0 2h-4v1h4V9zm2-6v9c0 .55-.45 1-1 1H9.5l-1 1-1-1H2c-.55 0-1-.45-1-1V3c0-.55.45-1 1-1h5.5l1 1 1-1H15c.55 0 1 .45 1 1zm-8 .5L7.5 3H2v9h6V3.5zm7-.5H9.5l-.5.5V12h6V3z"/></svg>
      Wiki
</a>

    <div class="reponav-dropdown js-menu-container">
      <button type="button" class="btn-link reponav-item reponav-dropdown js-menu-target " data-no-toggle aria-expanded="false" aria-haspopup="true">
        Insights
        <svg aria-hidden="true" class="octicon octicon-triangle-down v-align-middle text-gray" height="11" version="1.1" viewBox="0 0 12 16" width="8"><path fill-rule="evenodd" d="M0 5l6 6 6-6z"/></svg>
      </button>
      <div class="dropdown-menu-content js-menu-content">
        <div class="dropdown-menu dropdown-menu-sw">
          <a class="dropdown-item" href="/onmyway133/fantastic-ios-architecture/pulse" data-skip-pjax>
            <svg aria-hidden="true" class="octicon octicon-pulse" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M11.5 8L8.8 5.4 6.6 8.5 5.5 1.6 2.38 8H0v2h3.6l.9-1.8.9 5.4L9 8.5l1.6 1.5H14V8z"/></svg>
            Pulse
          </a>
          <a class="dropdown-item" href="/onmyway133/fantastic-ios-architecture/graphs" data-skip-pjax>
            <svg aria-hidden="true" class="octicon octicon-graph" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M16 14v1H0V0h1v14h15zM5 13H3V8h2v5zm4 0H7V3h2v10zm4 0h-2V6h2v7z"/></svg>
            Graphs
          </a>
        </div>
      </div>
    </div>
</nav>

      </div>
    </div>

<div class="container new-discussion-timeline experiment-repo-nav">
  <div class="repository-content">

    
  <a href="/onmyway133/fantastic-ios-architecture/blob/3ad43cd0c3014589f407c9a036c7f8bf0cf13057/README.md" class="d-none js-permalink-shortcut" data-hotkey="y">Permalink</a>

  <!-- blob contrib key: blob_contributors:v21:34bc81b45b1c4793d195466a17ffdb57 -->

  <div class="file-navigation js-zeroclipboard-container">
    
<div class="select-menu branch-select-menu js-menu-container js-select-menu float-left">
  <button class=" btn btn-sm select-menu-button js-menu-target css-truncate" data-hotkey="w"
    
    type="button" aria-label="Switch branches or tags" aria-expanded="false" aria-haspopup="true">
      <i>Branch:</i>
      <span class="js-select-button css-truncate-target">master</span>
  </button>

  <div class="select-menu-modal-holder js-menu-content js-navigation-container" data-pjax>

    <div class="select-menu-modal">
      <div class="select-menu-header">
        <svg aria-label="Close" class="octicon octicon-x js-menu-close" height="16" role="img" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48z"/></svg>
        <span class="select-menu-title">Switch branches/tags</span>
      </div>

      <div class="select-menu-filters">
        <div class="select-menu-text-filter">
          <input type="text" aria-label="Filter branches/tags" id="context-commitish-filter-field" class="form-control js-filterable-field js-navigation-enable" placeholder="Filter branches/tags">
        </div>
        <div class="select-menu-tabs">
          <ul>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="branches" data-filter-placeholder="Filter branches/tags" class="js-select-menu-tab" role="tab">Branches</a>
            </li>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="tags" data-filter-placeholder="Find a tag…" class="js-select-menu-tab" role="tab">Tags</a>
            </li>
          </ul>
        </div>
      </div>

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="branches" role="menu">

        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


            <a class="select-menu-item js-navigation-item js-navigation-open selected"
               href="/onmyway133/fantastic-ios-architecture/blob/master/README.md"
               data-name="master"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                master
              </span>
            </a>
        </div>

          <div class="select-menu-no-results">Nothing to show</div>
      </div>

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="tags">
        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


        </div>

        <div class="select-menu-no-results">Nothing to show</div>
      </div>

    </div>
  </div>
</div>

    <div class="BtnGroup float-right">
      <a href="/onmyway133/fantastic-ios-architecture/find/master"
            class="js-pjax-capture-input btn btn-sm BtnGroup-item"
            data-pjax
            data-hotkey="t">
        Find file
      </a>
      <button aria-label="Copy file path to clipboard" class="js-zeroclipboard btn btn-sm BtnGroup-item tooltipped tooltipped-s" data-copied-hint="Copied!" type="button">Copy path</button>
    </div>
    <div class="breadcrumb js-zeroclipboard-target">
      <span class="repo-root js-repo-root"><span class="js-path-segment"><a href="/onmyway133/fantastic-ios-architecture"><span>fantastic-ios-architecture</span></a></span></span><span class="separator">/</span><strong class="final-path">README.md</strong>
    </div>
  </div>


  
  <div class="commit-tease">
      <span class="float-right">
        <a class="commit-tease-sha" href="/onmyway133/fantastic-ios-architecture/commit/3ad43cd0c3014589f407c9a036c7f8bf0cf13057" data-pjax>
          3ad43cd
        </a>
        <relative-time datetime="2017-08-07T13:48:09Z">Aug 7, 2017</relative-time>
      </span>
      <div>
        <img alt="@onmyway133" class="avatar" height="20" src="https://avatars3.githubusercontent.com/u/2284279?v=4&amp;s=40" width="20" />
        <a href="/onmyway133" class="user-mention" rel="author">onmyway133</a>
          <a href="/onmyway133/fantastic-ios-architecture/commit/3ad43cd0c3014589f407c9a036c7f8bf0cf13057" class="message" data-pjax="true" title="Update README.md">Update README.md</a>
      </div>

    <div class="commit-tease-contributors">
      <button type="button" class="btn-link muted-link contributors-toggle" data-facebox="#blob_contributors_box">
        <strong>6</strong>
         contributors
      </button>
          <a class="avatar-link tooltipped tooltipped-s" aria-label="onmyway133" href="/onmyway133/fantastic-ios-architecture/commits/master/README.md?author=onmyway133"><img alt="@onmyway133" class="avatar" height="20" src="https://avatars3.githubusercontent.com/u/2284279?v=4&amp;s=40" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="dagio" href="/onmyway133/fantastic-ios-architecture/commits/master/README.md?author=dagio"><img alt="@dagio" class="avatar" height="20" src="https://avatars3.githubusercontent.com/u/74581?v=4&amp;s=40" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="shengzhe" href="/onmyway133/fantastic-ios-architecture/commits/master/README.md?author=shengzhe"><img alt="@shengzhe" class="avatar" height="20" src="https://avatars1.githubusercontent.com/u/2221872?v=4&amp;s=40" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="buguibu" href="/onmyway133/fantastic-ios-architecture/commits/master/README.md?author=buguibu"><img alt="@buguibu" class="avatar" height="20" src="https://avatars1.githubusercontent.com/u/2544273?v=4&amp;s=40" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="antonyalkmim" href="/onmyway133/fantastic-ios-architecture/commits/master/README.md?author=antonyalkmim"><img alt="@antonyalkmim" class="avatar" height="20" src="https://avatars0.githubusercontent.com/u/6514332?v=4&amp;s=40" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="amitshekhariitbhu" href="/onmyway133/fantastic-ios-architecture/commits/master/README.md?author=amitshekhariitbhu"><img alt="@amitshekhariitbhu" class="avatar" height="20" src="https://avatars3.githubusercontent.com/u/9877145?v=4&amp;s=40" width="20" /> </a>


    </div>

    <div id="blob_contributors_box" style="display:none">
      <h2 class="facebox-header" data-facebox-id="facebox-header">Users who have contributed to this file</h2>
      <ul class="facebox-user-list" data-facebox-id="facebox-description">
          <li class="facebox-user-list-item">
            <img alt="@onmyway133" height="24" src="https://avatars1.githubusercontent.com/u/2284279?v=4&amp;s=48" width="24" />
            <a href="/onmyway133">onmyway133</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@dagio" height="24" src="https://avatars1.githubusercontent.com/u/74581?v=4&amp;s=48" width="24" />
            <a href="/dagio">dagio</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@shengzhe" height="24" src="https://avatars3.githubusercontent.com/u/2221872?v=4&amp;s=48" width="24" />
            <a href="/shengzhe">shengzhe</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@buguibu" height="24" src="https://avatars3.githubusercontent.com/u/2544273?v=4&amp;s=48" width="24" />
            <a href="/buguibu">buguibu</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@antonyalkmim" height="24" src="https://avatars2.githubusercontent.com/u/6514332?v=4&amp;s=48" width="24" />
            <a href="/antonyalkmim">antonyalkmim</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@amitshekhariitbhu" height="24" src="https://avatars1.githubusercontent.com/u/9877145?v=4&amp;s=48" width="24" />
            <a href="/amitshekhariitbhu">amitshekhariitbhu</a>
          </li>
      </ul>
    </div>
  </div>

  <div class="file">
    <div class="file-header">
  <div class="file-actions">

    <div class="BtnGroup">
      <a href="/onmyway133/fantastic-ios-architecture/raw/master/README.md" class="btn btn-sm BtnGroup-item" id="raw-url">Raw</a>
        <a href="/onmyway133/fantastic-ios-architecture/blame/master/README.md" class="btn btn-sm js-update-url-with-hash BtnGroup-item" data-hotkey="b">Blame</a>
      <a href="/onmyway133/fantastic-ios-architecture/commits/master/README.md" class="btn btn-sm BtnGroup-item" rel="nofollow">History</a>
    </div>

        <a class="btn-octicon tooltipped tooltipped-nw"
           href="https://desktop.github.com"
           aria-label="Open this file in GitHub Desktop"
           data-ga-click="Repository, open with desktop, type:windows">
            <svg aria-hidden="true" class="octicon octicon-device-desktop" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M15 2H1c-.55 0-1 .45-1 1v9c0 .55.45 1 1 1h5.34c-.25.61-.86 1.39-2.34 2h8c-1.48-.61-2.09-1.39-2.34-2H15c.55 0 1-.45 1-1V3c0-.55-.45-1-1-1zm0 9H1V3h14v8z"/></svg>
        </a>

        <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/onmyway133/fantastic-ios-architecture/edit/master/README.md" class="inline-form js-update-url-with-hash" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="X5y964fHaovRvKHXGMeNnIALSzB8u1OuJqzpzr5Afl3TjSITNhIdbmdHqpZYJ31C5vtffbss9t9QGNN+zbJU+w==" /></div>
          <button class="btn-octicon tooltipped tooltipped-nw" type="submit"
            aria-label="Fork this project and edit the file" data-hotkey="e" data-disable-with>
            <svg aria-hidden="true" class="octicon octicon-pencil" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M0 12v3h3l8-8-3-3-8 8zm3 2H1v-2h1v1h1v1zm10.3-9.3L12 6 9 3l1.3-1.3a.996.996 0 0 1 1.41 0l1.59 1.59c.39.39.39 1.02 0 1.41z"/></svg>
          </button>
</form>        <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/onmyway133/fantastic-ios-architecture/delete/master/README.md" class="inline-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="FBwUS40DiaRVXEsVyIUiPRSYx2eDLVQ1toY8m22Y4fFtbjz2tO8+HAmtrAUsOO8obXAGyHhlxkzI7xzxjekJZw==" /></div>
          <button class="btn-octicon btn-octicon-danger tooltipped tooltipped-nw" type="submit"
            aria-label="Fork this project and delete the file" data-disable-with>
            <svg aria-hidden="true" class="octicon octicon-trashcan" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M11 2H9c0-.55-.45-1-1-1H5c-.55 0-1 .45-1 1H2c-.55 0-1 .45-1 1v1c0 .55.45 1 1 1v9c0 .55.45 1 1 1h7c.55 0 1-.45 1-1V5c.55 0 1-.45 1-1V3c0-.55-.45-1-1-1zm-1 12H3V5h1v8h1V5h1v8h1V5h1v8h1V5h1v9zm1-10H2V3h9v1z"/></svg>
          </button>
</form>  </div>

  <div class="file-info">
      272 lines (198 sloc)
      <span class="file-info-divider"></span>
    16.4 KB
  </div>
</div>

    
  <div id="readme" class="readme blob instapaper_body">
    <article class="markdown-body entry-content" itemprop="text"><h1><a id="user-content-fantastic-ios-architecture" class="anchor" href="#fantastic-ios-architecture" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>fantastic-ios-architecture</h1>
<p>Better ways to structure apps</p>
<p><a href="/onmyway133/fantastic-ios-architecture/blob/master/Screenshots/Banner.png" target="_blank"><img src="/onmyway133/fantastic-ios-architecture/raw/master/Screenshots/Banner.png" alt="" style="max-width:100%;"></a></p>
<h1><a id="user-content-content" class="anchor" href="#content" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Content</h1>

<ul>
<li><a href="#general">General</a></li>
<li><a href="#clean-architecture">Clean Architecture</a></li>
<li><a href="#unidirectional-data-flow">Unidirectional Data Flow</a></li>
<li><a href="#mvc">MVC</a></li>
<li><a href="#viper">VIPER</a></li>
<li><a href="#mvvm">MVVM</a></li>
<li><a href="#data-source">Data Source</a></li>
<li><a href="#sync">Sync</a></li>
<li><a href="#cache">Cache</a></li>
<li><a href="#asynchronous-programming">Asynchronous Programming</a></li>
<li><a href="#persistence">Persistence</a></li>
<li><a href="#navigation">Navigation</a></li>
</ul>

<h1><a id="user-content-general" class="anchor" href="#general" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>General</h1>
<h3><a id="user-content-posts" class="anchor" href="#posts" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Posts</h3>
<ul>
<li><a href="http://www.fantageek.com/blog/2015/12/03/clean-cocoa/">Clean Cocoa</a> <g-emoji alias="star" fallback-src="https://assets-cdn.github.com/images/icons/emoji/unicode/2b50.png" ios-version="6.0">⭐️</g-emoji></li>
<li><a href="http://albertodebortoli.github.io/blog/2014/09/03/flow-controllers-on-ios-for-a-better-navigation-control/">Flow Controllers on iOS for a Better Navigation Control</a></li>
<li><a href="http://doing-it-wrong.mikeweller.com/2013/06/ios-app-architecture-and-tdd-1.html">iOS Development: You're Doing It Wrong</a></li>
<li><a href="http://jpellat.com/how-to-separate-view-controllers-from-his-view-logic/">How to separate view controllers from their view logic</a></li>
<li><a href="http://khanlou.com/2014/09/8-patterns-to-help-you-destroy-massive-view-controller/">8 Patterns to Help You Destroy Massive View Controller</a></li>
<li><a href="http://mattgemmell.com/api-design/">API Design</a></li>
<li><a href="http://chris.eidhof.nl/posts/intentions.html">Intentions</a></li>
<li><a href="http://www.teehanlax.com/blog/model-view-viewmodel-for-ios/">Model-View-ViewModel for iOS</a></li>
<li><a href="http://www.cocoawithlove.com/2008/11/singletons-appdelegates-and-top-level.html">Singletons, AppDelegates and top-level data.</a></li>
<li><a href="http://kickingbear.com/blog/archives/9">Collection Extensions</a></li>
<li><a href="https://medium.com/ios-apprentice/model-view-controller-presenter-8bb4149fa5ef">Model View Controller Presenter</a></li>
<li><a href="http://khanlou.com/2014/03/model-view-whatever/">Model View Whatever</a></li>
<li><a href="https://medium.com/medium-eng/how-we-modularized-mediums-ios-codebase-8f8f26965c76">How We Modularized Medium’s iOS codebase</a></li>
<li><a href="http://blog.vikingosegundo.de/2014/06/16/lighter-view-controller-swift/">Lighter View Controller Swift</a></li>
<li><a href="http://merowing.info/2016/01/improve-your-ios-architecture-with-flowcontrollers/">Improve your iOS Architecture with FlowControllers</a></li>
<li><a href="http://khanlou.com/2015/12/massive-view-controller/">Massive View Controller</a></li>
<li><a href="https://slack-files.com/T051G5Y6D-F0HABHKDK-8e9141e191">Modern application architectures (Reactive programming, MVVM and beyond)</a></li>
<li><a href="https://yalantis.com/blog/tree-of-models-as-an-alternative-app-architecture-model/">“Tree of Models” as an Alternative App Architecture Model</a> <g-emoji alias="star" fallback-src="https://assets-cdn.github.com/images/icons/emoji/unicode/2b50.png" ios-version="6.0">⭐️</g-emoji></li>
<li><a href="https://gist.github.com/andymatuschak/d5f0a8730ad601bcccae97e8398e25b2">A composable pattern for pure state machines with effects</a></li>
<li><a href="https://christiantietze.de/posts/2016/08/mvvm-is-okay-for-what-it-does/">MVVM Is Quite Okay at What It Is Supposed to Do</a></li>
<li><a href="https://swifting.io/blog/2016/09/07/architecture-wars-a-new-hope/">Architectures comparison</a></li>
</ul>
<h3><a id="user-content-appdelegate" class="anchor" href="#appdelegate" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>AppDelegate</h3>
<ul>
<li><a href="http://sizeof.io/service-oriented-appdelegate/">SERVICE-ORIENTED APPDELEGATE</a></li>
<li><a href="http://www.fantageek.com/blog/2015/10/31/lighter-appdelegate/">Lighter AppDelegate</a></li>
<li><a href="https://medium.com/ios-os-x-development/pluggableapplicationdelegate-e50b2c5d97dd#.scovfjixy">Service-oriented AppDelegate</a></li>
</ul>
<h3><a id="user-content-videos" class="anchor" href="#videos" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Videos</h3>
<ul>
<li><a href="https://www.youtube.com/watch?v=TCPWckSi0Xs&amp;feature=youtu.be">Platformizing UI code</a></li>
<li><a href="https://realm.io/news/pragma-hannes-verlinde-statelessness-react-native/">The State of Statelessness</a></li>
<li><a href="http://slideslive.com/38897361/good-ios-application-architecture-en">Good iOS Application Architecture</a></li>
</ul>
<h3><a id="user-content-misc" class="anchor" href="#misc" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Misc</h3>
<ul>
<li><a href="https://github.com/mdiep/Logician">Logician</a> Logic programming in Swift</li>
<li><a href="https://github.com/bricepollock/modular-architecture">modular-architecture</a> Examples of iOS Modular Architecture in Swift</li>
<li><a href="https://github.com/thoughtbot/Delta">Delta</a> Delta takes an app that has custom state management spread throughout all the VCs and simplifies it by providing a simple interface to change state and subscribe to its changes.</li>
<li><a href="https://github.com/artsy/eigen/blob/master/docs/overview.md">eigen</a> The Art World in Your Pocket or Your Trendy Tech Company's Tote, Artsy's iOS app</li>
<li><a href="https://eng.uber.com/new-rider-app/">ENGINEERING THE ARCHITECTURE BEHIND UBER’S NEW RIDER APP</a></li>
</ul>
<h1><a id="user-content-clean-architecture" class="anchor" href="#clean-architecture" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Clean Architecture</h1>
<h3><a id="user-content-posts-1" class="anchor" href="#posts-1" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Posts</h3>
<ul>
<li><a href="http://clean-swift.com/clean-swift-ios-architecture/">Clean Swift iOS Architecture for Fixing Massive View Controller</a></li>
</ul>
<h3><a id="user-content-repos" class="anchor" href="#repos" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Repos</h3>
<ul>
<li><a href="https://github.com/Clean-Swift/CleanStore">CleanStore</a> A sample iOS app built using the Clean Swift architecture</li>
<li><a href="https://github.com/sergdort/CleanArchitectureRxSwift">CleanArchitectureRxSwift</a> Example of Clean Architecture of iOS app using RxSwift <g-emoji alias="rocket" fallback-src="https://assets-cdn.github.com/images/icons/emoji/unicode/1f680.png" ios-version="6.0">🚀</g-emoji></li>
</ul>
<h1><a id="user-content-unidirectional-data-flow" class="anchor" href="#unidirectional-data-flow" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Unidirectional Data Flow</h1>
<h3><a id="user-content-posts-2" class="anchor" href="#posts-2" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Posts</h3>
<ul>
<li><a href="https://realm.io/news/benji-encz-unidirectional-data-flow-swift/">Unidirectional Data Flow in Swift: An Alternative to Massive View Controllers</a></li>
<li><a href="https://corner.squareup.com/2015/12/ziggurat-ios-app-architecture.html">Ziggurat iOS App Architecture</a></li>
<li><a href="https://github.com/alanf/ziggurat">ziggurat</a> App architecture with one-way data data flow and view models</li>
<li><a href="https://www.youtube.com/watch?v=4cP1p5VOrSI">Rethinking iOS App Architecture Using a One Way Data Flow</a></li>
<li><a href="https://medium.com/design-x-code/elmification-of-swift-af14b7f92b30#.7twj79puf">Elmification of Swift</a></li>
<li><a href="https://github.com/sahandnayebaziz/StateView">StateView</a> Views that automatically update themselves.</li>
<li><a href="https://github.com/alexdrone/Render">Render</a> Swift and UIKit a la React.</li>
<li><a href="http://blog.benjamin-encz.de/post/real-world-flux-ios/">Real World Flux Architecture on iOS</a> <g-emoji alias="star" fallback-src="https://assets-cdn.github.com/images/icons/emoji/unicode/2b50.png" ios-version="6.0">⭐️</g-emoji></li>
<li><a href="https://realm.io/news/altconf-benji-encz-uikit-inside-out-declarative-programming">Turning UIKit Inside Out</a> <g-emoji alias="star" fallback-src="https://assets-cdn.github.com/images/icons/emoji/unicode/2b50.png" ios-version="6.0">⭐️</g-emoji></li>
<li><a href="http://willowtreeapps.com/ideas/app-coordinators-and-redux-on-ios/">App Coordinators and Redux on iOS</a></li>
<li><a href="https://www.raywenderlich.com/155815/reswift-tutorial-memory-game-app">ReSwift Tutorial: Memory Game App</a></li>
</ul>
<h3><a id="user-content-videos-1" class="anchor" href="#videos-1" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Videos</h3>
<ul>
<li><a href="https://realm.io/news/unidirectional-data-flow-in-swift/">Building a Unidirectional Data Flow App in Swift with Realm</a></li>
</ul>
<h3><a id="user-content-repos-1" class="anchor" href="#repos-1" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Repos</h3>
<ul>
<li><a href="https://github.com/ReSwift/ReSwift">ReSwift</a> Unidirectional Data Flow in Swift - Inspired by Redux <g-emoji alias="star" fallback-src="https://assets-cdn.github.com/images/icons/emoji/unicode/2b50.png" ios-version="6.0">⭐️</g-emoji><g-emoji alias="star" fallback-src="https://assets-cdn.github.com/images/icons/emoji/unicode/2b50.png" ios-version="6.0">⭐️</g-emoji><g-emoji alias="star" fallback-src="https://assets-cdn.github.com/images/icons/emoji/unicode/2b50.png" ios-version="6.0">⭐️</g-emoji></li>
<li><a href="https://github.com/jarsen/Reactor">Reactor</a> Unidirectional data flow in Swift</li>
<li><a href="https://github.com/hyperoslo/Aftermath">Aftermath</a> Stateless message-driven micro-framework in Swift. <g-emoji alias="star" fallback-src="https://assets-cdn.github.com/images/icons/emoji/unicode/2b50.png" ios-version="6.0">⭐️</g-emoji><g-emoji alias="star" fallback-src="https://assets-cdn.github.com/images/icons/emoji/unicode/2b50.png" ios-version="6.0">⭐️</g-emoji></li>
<li><a href="https://github.com/alexdrone/Render">Renderer</a> Swift and UIKit a la React.</li>
<li><a href="https://github.com/joshaber/Few.swift">Few.swift</a> Views as functions of their state.</li>
<li><a href="https://github.com/yonekawa/SwiftFlux">SwiftFlux</a> A type-safe Flux implementation for Swift</li>
<li><a href="https://github.com/BendingSpoons/katana-swift">katana-swift</a> Swift Apps in a Swoosh</li>
<li><a href="https://github.com/alexdrone/Dispatch">Dispatch</a> Multi-store Flux implementation in Swift.</li>
<li><a href="https://github.com/ReactorKit/ReactorKit">ReactorKit</a> A framework for reactive and unidirectional Swift application architecture <g-emoji alias="rocket" fallback-src="https://assets-cdn.github.com/images/icons/emoji/unicode/1f680.png" ios-version="6.0">🚀</g-emoji> <g-emoji alias="rocket" fallback-src="https://assets-cdn.github.com/images/icons/emoji/unicode/1f680.png" ios-version="6.0">🚀</g-emoji></li>
<li><a href="https://github.com/kzaher/RxFeedback">RxFeedback</a> Architecture for RxSwift</li>
<li><a href="https://github.com/chriseidhof/tea-in-swift">tea-in-swift</a> The Elm Architecture in Swift</li>
</ul>
<h1><a id="user-content-mvc" class="anchor" href="#mvc" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>MVC</h1>
<h3><a id="user-content-posts-3" class="anchor" href="#posts-3" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Posts</h3>
<ul>
<li><a href="https://www.cocoawithlove.com/blog/mvc-and-cocoa.html">Looking at Model-View-Controller in Cocoa</a></li>
<li><a href="https://badootech.badoo.com/do-mvc-like-its-1979-da62304f6568">Do MVC like it’s 1979</a></li>
</ul>
<h1><a id="user-content-viper" class="anchor" href="#viper" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>VIPER</h1>
<h3><a id="user-content-posts-4" class="anchor" href="#posts-4" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Posts</h3>
<ul>
<li><a href="http://mutualmobile.github.io/blog/2013/12/04/viper-introduction/">Introduction to VIPER</a></li>
<li><a href="http://www.objc.io/issues/13-architecture/viper/">Architecting iOS Apps with VIPER</a></li>
<li><a href="https://medium.com/brigade-engineering/brigades-experience-using-an-mvc-alternative-36ef1601a41f">Brigade’s Experience Using an MVC Alternative</a></li>
<li><a href="http://iosunittesting.com/tdd-with-viper/">First Observations on TDD with VIPER</a></li>
<li><a href="https://realm.io/news/modular-ios-apps/">Building Modular iOS Apps</a></li>
<li><a href="http://devchat.tv/iphreaks/064-iphreaks-show-viper-with-conrad-stoll-and-jeff-gilbert">iPhreaks Show – VIPER with Conrad Stoll and Jeff Gilbert</a></li>
<li><a href="https://www.youtube.com/watch?v=OX4rLAJC7lw">Clean Architecture - VIPER by Redbooth</a></li>
<li><a href="https://realm.io/news/altconf-brice-pollock-250-days-shipping-with-swift-and-viper/">250 Days Shipping With Swift and VIPER</a></li>
<li><a href="http://www.outware.com.au/insights/ios-architecture-real-life-viper/">IOS ARCHITECTURE: REAL LIFE VIPER</a></li>
<li><a href="https://medium.com/ios-os-x-development/humble-object-pattern-in-swift-de5efe8fe05a#.dmkvdbjoy">Humble Object Pattern in Swift</a></li>
<li><a href="https://medium.com/ios-os-x-development/ios-architecture-patterns-ecba4c38de52#.tliwdfd60">iOS Architecture Patterns Demystifying MVC, MVP, MVVM and VIPER</a></li>
<li><a href="https://www.quora.com/Should-I-use-Viper-architecture-for-my-next-iOS-application-or-it-is-still-very-new-to-use">Should I use Viper architecture for my next iOS application, or it is still very new to use?</a></li>
<li><a href="https://swifting.io/blog/2016/03/07/8-viper-to-be-or-not-to-be/">VIPER to be or not to be?</a></li>
<li><a href="https://www.ckl.io/blog/ios-project-architecture-using-viper/">iOS Project Architecture: Using VIPER</a></li>
<li><a href="https://github.com/JeanLebrument/iOSModulesArchitecture">iOSModulesArchitecture</a> Quick example of how divide an app into modules to respect the SOLID principles</li>
<li><a href="http://www.mttnow.com/blog/architecting-mobile-apps-with-bviper-modules">ARCHITECTING MOBILE APPS WITH (B)VIPER MODULES - A STRUCTURED ENGINEERING APPROACH FOR BIG MOBILE APPS</a></li>
<li><a href="https://speakerdeck.com/sergigracia/clean-architecture-viper">Clean Architecture - VIPER at Redbooth</a> by <a href="https://twitter.com/sergigracia">@sergigracia</a></li>
<li><a href="https://swifting.io/blog/2016/03/07/8-viper-to-be-or-not-to-be/">VIPER to be or not to be</a></li>
<li><a href="https://blog.mindorks.com/building-ios-app-with-viper-architecture-8109acc72227">Building iOS App With VIPER Architecture</a></li>
<li><a href="https://github.com/ferranabello/Viperit">Viper Framework for iOS using Swift v3</a></li>
<li><a href="http://www.thinkandbuild.it/viper-s-writing-your-own-architecture-and-understand-its-importance-part-3/">VIPER-S: WRITING YOUR OWN ARCHITECTURE AND UNDERSTAND ITS IMPORTANCE (PART 3)</a></li>
</ul>
<h3><a id="user-content-repos-2" class="anchor" href="#repos-2" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Repos</h3>
<ul>
<li><a href="https://github.com/MindorksOpenSource/iOS-Viper-Architecture">iOS-Viper-Architecture</a> A detailed sample app that implements VIPER architecture</li>
<li><a href="https://github.com/RoRoche/iOSSwiftStarter">iOSSwiftStarter</a> A sample iOS app written in Swift using the VIPER architecture.</li>
</ul>
<h1><a id="user-content-mvvm" class="anchor" href="#mvvm" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>MVVM</h1>
<h3><a id="user-content-posts-5" class="anchor" href="#posts-5" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Posts</h3>
<ul>
<li><a href="https://www.objc.io/issues/13-architecture/mvvm/">Introduction to MVVM</a></li>
<li><a href="http://khanlou.com/2015/12/mvvm-is-not-very-good/">MVVM is Not Very Good</a></li>
<li><a href="http://blog.xebia.com/simplification-of-ios-view-controllers-mvvm-or-presentation-controls/">Simplification Of IOS View Controllers: MVVM Or Presentation Controls?</a></li>
<li><a href="http://twocentstudios.com/2014/06/08/on-mvvm-and-architecture-questions/">On MVVM, and Architecture Questions</a></li>
<li><a href="https://github.com/ivanbruel/Reddit-MVVM-Benchmark">Reddit-MVVM-Benchmark</a> MVVM with FRP Benchmark project</li>
</ul>
<h3><a id="user-content-repos-3" class="anchor" href="#repos-3" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Repos</h3>
<ul>
<li><a href="https://github.com/devxoul/TheReactiveArchitecture">TheReactiveArchitecture</a> The modern and reactive architecture for RxSwift application</li>
<li><a href="https://github.com/kickstarter/native-docs/blob/master/vm-structure.md">kickstarter vm structure</a> Rx input and output</li>
</ul>
<h1><a id="user-content-data-source" class="anchor" href="#data-source" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Data Source</h1>
<h3><a id="user-content-posts-6" class="anchor" href="#posts-6" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Posts</h3>
<ul>
<li><a href="https://yalantis.com/blog/lightweight-ios-view-controllers-separate-data-sources-guided-mvc/">Lightweight iOS View Controllers</a></li>
<li><a href="http://oleb.net/blog/2014/06/apples-take-on-app-architecture/">Apple’s Take on App Architecture</a></li>
<li><a href="http://www.iosnomad.com/blog/2014/4/21/fluent-pagination">Fluent Pagination - no more jumpy scrolling</a></li>
<li><a href="https://github.com/zwaldowski/AdvancedCollectionView">AdvancedCollectionView</a></li>
<li><a href="http://gosuwachu.io/2014/01/12/uitableview-controller/">iOS: UITableView controller</a></li>
<li><a href="http://khanlou.com/2015/04/nestable/">Nestable</a></li>
<li><a href="http://engineeringblog.yelp.com/2015/06/advanced-uitableviews-made-simple-yltableview.html">Advanced UITableViews Made Simple: YLTableView</a></li>
<li><a href="http://holko.pl/2016/01/05/typed-table-view-controller/">Typed, yet Flexible Table View Controller</a></li>
<li><a href="https://engineering.kitchenstories.io/this-simple-trick-will-change-how-you-think-about-table-views-706193654974#.raaqvz1yi">Complex table view state changes made easy</a></li>
</ul>
<h3><a id="user-content-videos-2" class="anchor" href="#videos-2" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Videos</h3>
<ul>
<li><a href="https://www.youtube.com/watch?v=vuCfKjOwZdU&amp;feature=youtu.be">UMT2016 - John Sundell - Building component-driven UIs at Spotify</a></li>
<li><a href="https://realm.io/news/tryswift-ryan-nystrom-refactoring-at-scale-lessons-learned-rewriting-instagram-feed/">Refactoring at Scale – Lessons Learned Rewriting Instagram’s Feed</a></li>
</ul>
<h3><a id="user-content-repos-4" class="anchor" href="#repos-4" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Repos</h3>
<ul>
<li><a href="https://github.com/jordanekay/Mensa">Mensa</a> Smart, modern table and collection views on iOS.</li>
<li><a href="https://github.com/rlopezdiez/RLDTableViewSuite">RLDTableViewSuite</a> Reusable table view controller, data source and delegate for all your UITableView needs</li>
<li><a href="https://github.com/MrAlek/PagedArray">PagedArray</a> A Swift data structure for easier pagination</li>
<li><a href="https://github.com/gonzalezreal/ReadingList">ReadingList</a> An example on using the Mantle Modeling Framework with Overcoat AFNetworking extension.</li>
<li><a href="https://github.com/DenHeadless/DTTableViewManager">DTTableViewManager</a> Protocol-oriented UITableView management, powered by generics and associated types.</li>
<li><a href="https://github.com/aschuch/StatefulViewController">StatefulViewController</a> Placeholder views based on content, loading, error or empty states</li>
<li><a href="https://github.com/hyperoslo/Spots">Spots</a> Spots is a view controller framework that makes your setup and future development blazingly fast <g-emoji alias="star" fallback-src="https://assets-cdn.github.com/images/icons/emoji/unicode/2b50.png" ios-version="6.0">⭐️</g-emoji><g-emoji alias="star" fallback-src="https://assets-cdn.github.com/images/icons/emoji/unicode/2b50.png" ios-version="6.0">⭐️</g-emoji></li>
<li><a href="https://github.com/jessesquires/JSQDataSourcesKit">JSQDataSourcesKit</a> Type-safe, value-oriented, composable data source objects that keep your view controllers light</li>
<li><a href="https://github.com/ben-g/autotable">AutoTablel</a> Demonstration of wrapping a UIKit API into a declarative API Layer</li>
<li><a href="https://github.com/spotify/HubFramework">HubFramework</a> Spotify’s component-driven UI framework for iOS <g-emoji alias="star" fallback-src="https://assets-cdn.github.com/images/icons/emoji/unicode/2b50.png" ios-version="6.0">⭐️</g-emoji><g-emoji alias="star" fallback-src="https://assets-cdn.github.com/images/icons/emoji/unicode/2b50.png" ios-version="6.0">⭐️</g-emoji><g-emoji alias="star" fallback-src="https://assets-cdn.github.com/images/icons/emoji/unicode/2b50.png" ios-version="6.0">⭐️</g-emoji></li>
<li><a href="https://github.com/facebook/componentkit">ComponentKit</a> A React-inspired view framework for iOS</li>
<li><a href="https://github.com/instagram/IGListKit">IGListKit</a> A data-driven UICollectionView framework for building fast and flexible lists. <g-emoji alias="star" fallback-src="https://assets-cdn.github.com/images/icons/emoji/unicode/2b50.png" ios-version="6.0">⭐️</g-emoji><g-emoji alias="star" fallback-src="https://assets-cdn.github.com/images/icons/emoji/unicode/2b50.png" ios-version="6.0">⭐️</g-emoji><g-emoji alias="star" fallback-src="https://assets-cdn.github.com/images/icons/emoji/unicode/2b50.png" ios-version="6.0">⭐️</g-emoji></li>
<li><a href="https://github.com/Jasonette/JASONETTE-iOS">JASONETTE-iOS</a> Native App over HTTP <g-emoji alias="star" fallback-src="https://assets-cdn.github.com/images/icons/emoji/unicode/2b50.png" ios-version="6.0">⭐️</g-emoji><g-emoji alias="star" fallback-src="https://assets-cdn.github.com/images/icons/emoji/unicode/2b50.png" ios-version="6.0">⭐️</g-emoji><g-emoji alias="rocket" fallback-src="https://assets-cdn.github.com/images/icons/emoji/unicode/1f680.png" ios-version="6.0">🚀</g-emoji></li>
<li><a href="https://github.com/aschuch/StatefulViewController">StatefulViewController</a> Placeholder views based on content, loading, error or empty states</li>
<li><a href="https://github.com/muukii/StackScrollView">StackScrollView</a> iOS Form UI Builder in Swift (powered by UICollectionView)</li>
<li><a href="https://github.com/justeat/ScrollingStackViewController">ScrollingStackViewController</a> A view controller that uses root views of child view controllers as views in a UIStackView.</li>
<li><a href="https://github.com/malcommac/ScrollingStackContainer">ScrollingStackContainer</a> Efficient Scrolling UIStackView in Swift</li>
</ul>
<h1><a id="user-content-sync" class="anchor" href="#sync" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Sync</h1>
<h3><a id="user-content-posts-7" class="anchor" href="#posts-7" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Posts</h3>
<ul>
<li><a href="https://realm.io/news/introducing-realm-mobile-platform/">Introducing the Realm Mobile Platform: Realtime Sync Plus Fully Open Source Databas</a></li>
</ul>
<h3><a id="user-content-repos-5" class="anchor" href="#repos-5" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Repos</h3>
<ul>
<li><a href="https://github.com/wireapp/wire-ios-sync-engine">wire-ios-sync-engine</a> iOS synchronization library for Wire</li>
</ul>
<h1><a id="user-content-cache" class="anchor" href="#cache" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Cache</h1>
<h3><a id="user-content-repos-6" class="anchor" href="#repos-6" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Repos</h3>
<ul>
<li><a href="https://github.com/hyperoslo/Cache">Cache</a> Nothing but Cache</li>
<li><a href="https://github.com/linkedin/RocketData">RocketData</a></li>
</ul>
<h3><a id="user-content-videos-3" class="anchor" href="#videos-3" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Videos</h3>
<ul>
<li><a href="https://realm.io/news/slug-peter-livesey-managing-consistency-immutable-models/">Managing Consistency of Immutable Models</a></li>
</ul>
<h1><a id="user-content-asynchronous-programming" class="anchor" href="#asynchronous-programming" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Asynchronous Programming</h1>
<h3><a id="user-content-posts-8" class="anchor" href="#posts-8" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Posts</h3>
<ul>
<li><a href="https://ashfurrow.com/blog/comparative-asynchronous-programming/">Comparative Asynchronous Programming</a></li>
<li><a href="http://adamborek.com/thinking-rxswift/">Thinking in RxSwift</a></li>
<li><a href="http://chris.eidhof.nl/post/reducers/">Reducers</a></li>
</ul>
<h3><a id="user-content-frameworks" class="anchor" href="#frameworks" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Frameworks</h3>
<ul>
<li><a href="https://github.com/ReactiveX/RxSwift">RxSwift</a> Reactive Programming in Swift</li>
<li><a href="https://github.com/danthorpe/Operations">Operations</a> A Swift framework inspired by WWDC 2015 Advanced NSOperations session.</li>
</ul>
<h1><a id="user-content-persistence" class="anchor" href="#persistence" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Persistence</h1>
<h3><a id="user-content-posts-9" class="anchor" href="#posts-9" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Posts</h3>
<ul>
<li><a href="https://medium.com/swift-programming/mvc-rs-8780e73e9ff4">MVC-RS</a></li>
<li><a href="https://medium.com/ios-os-x-development/the-missing-light-persistence-layer-for-swift-35ce75d02d47">The Missing Light Persistence Layer for Swift</a></li>
<li><a href="http://albertodebortoli.com/blog/2017/03/02/How-to-abstract-your-persistence-layer-and-migrate-to-another-one-on-iOS-with-JustPersist/">How to Abstract Your Persistence Layer and Migrate to Another One on iOS With JustPersist</a></li>
</ul>
<h3><a id="user-content-repos-7" class="anchor" href="#repos-7" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Repos</h3>
<ul>
<li><a href="https://github.com/casatwy/CTPersistance">CTPersistance</a></li>
<li><a href="https://github.com/justeat/JustPersist">JustPersist</a></li>
<li><a href="https://github.com/nickoneill/Pantry">Pantry</a></li>
</ul>
<h1><a id="user-content-navigation" class="anchor" href="#navigation" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Navigation</h1>
<h3><a id="user-content-posts-10" class="anchor" href="#posts-10" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Posts</h3>
<ul>
<li><a href="http://khanlou.com/2015/10/coordinators-redux/">Coordinators Redux</a></li>
</ul>
<h3><a id="user-content-repos-8" class="anchor" href="#repos-8" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Repos</h3>
<ul>
<li><a href="https://github.com/hyperoslo/Compass">Compass</a> Compass helps you setup a central navigation system for your application</li>
</ul>
<h2><a id="user-content-licence" class="anchor" href="#licence" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Licence</h2>
<p>This project is released under the MIT license. See LICENSE.md.</p>
</article>
  </div>

  </div>

  <button type="button" data-facebox="#jump-to-line" data-facebox-class="linejump" data-hotkey="l" class="d-none">Jump to Line</button>
  <div id="jump-to-line" style="display:none">
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="" class="js-jump-to-line-form" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
      <input class="form-control linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line&hellip;" aria-label="Jump to line" autofocus>
      <button type="submit" class="btn">Go</button>
</form>  </div>

  </div>
  <div class="modal-backdrop js-touch-events"></div>
</div>

    </div>
  </div>

  </div>

      
<div class="footer container-lg px-3" role="contentinfo">
  <div class="position-relative d-flex flex-justify-between py-6 mt-6 f6 text-gray border-top border-gray-light ">
    <ul class="list-style-none d-flex flex-wrap ">
      <li class="mr-3">&copy; 2017 <span title="0.23588s from unicorn-1735160527-mhr9j">GitHub</span>, Inc.</li>
        <li class="mr-3"><a href="https://github.com/site/terms" data-ga-click="Footer, go to terms, text:terms">Terms</a></li>
        <li class="mr-3"><a href="https://github.com/site/privacy" data-ga-click="Footer, go to privacy, text:privacy">Privacy</a></li>
        <li class="mr-3"><a href="https://github.com/security" data-ga-click="Footer, go to security, text:security">Security</a></li>
        <li class="mr-3"><a href="https://status.github.com/" data-ga-click="Footer, go to status, text:status">Status</a></li>
        <li><a href="https://help.github.com" data-ga-click="Footer, go to help, text:help">Help</a></li>
    </ul>

    <a href="https://github.com" aria-label="Homepage" class="footer-octicon" title="GitHub">
      <svg aria-hidden="true" class="octicon octicon-mark-github" height="24" version="1.1" viewBox="0 0 16 16" width="24"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"/></svg>
</a>
    <ul class="list-style-none d-flex flex-wrap ">
        <li class="mr-3"><a href="https://github.com/contact" data-ga-click="Footer, go to contact, text:contact">Contact GitHub</a></li>
      <li class="mr-3"><a href="https://developer.github.com" data-ga-click="Footer, go to api, text:api">API</a></li>
      <li class="mr-3"><a href="https://training.github.com" data-ga-click="Footer, go to training, text:training">Training</a></li>
      <li class="mr-3"><a href="https://shop.github.com" data-ga-click="Footer, go to shop, text:shop">Shop</a></li>
        <li class="mr-3"><a href="https://github.com/blog" data-ga-click="Footer, go to blog, text:blog">Blog</a></li>
        <li><a href="https://github.com/about" data-ga-click="Footer, go to about, text:about">About</a></li>

    </ul>
  </div>
</div>



  <div id="ajax-error-message" class="ajax-error-message flash flash-error">
    <svg aria-hidden="true" class="octicon octicon-alert" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M8.865 1.52c-.18-.31-.51-.5-.87-.5s-.69.19-.87.5L.275 13.5c-.18.31-.18.69 0 1 .19.31.52.5.87.5h13.7c.36 0 .69-.19.86-.5.17-.31.18-.69.01-1L8.865 1.52zM8.995 13h-2v-2h2v2zm0-3h-2V6h2v4z"/></svg>
    <button type="button" class="flash-close js-flash-close js-ajax-error-dismiss" aria-label="Dismiss error">
      <svg aria-hidden="true" class="octicon octicon-x" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48z"/></svg>
    </button>
    You can't perform that action at this time.
  </div>


    
    <script crossorigin="anonymous" integrity="sha256-CDJgz5igmxVYa+cL5uSEJrHNCNvKIn1MgYqR+prYSRE=" src="https://assets-cdn.github.com/assets/frameworks-083260cf98a09b15586be70be6e48426b1cd08dbca227d4c818a91fa9ad84911.js"></script>
    
    <script async="async" crossorigin="anonymous" integrity="sha256-qWxqa+XT+fXNH2/SHT9dg1WMTsIPeiLOMsTenpc1Ndg=" src="https://assets-cdn.github.com/assets/github-a96c6a6be5d3f9f5cd1f6fd21d3f5d83558c4ec20f7a22ce32c4de9e973535d8.js"></script>
    
    
    
    
  <div class="js-stale-session-flash stale-session-flash flash flash-warn flash-banner d-none">
    <svg aria-hidden="true" class="octicon octicon-alert" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M8.865 1.52c-.18-.31-.51-.5-.87-.5s-.69.19-.87.5L.275 13.5c-.18.31-.18.69 0 1 .19.31.52.5.87.5h13.7c.36 0 .69-.19.86-.5.17-.31.18-.69.01-1L8.865 1.52zM8.995 13h-2v-2h2v2zm0-3h-2V6h2v4z"/></svg>
    <span class="signed-in-tab-flash">You signed in with another tab or window. <a href="">Reload</a> to refresh your session.</span>
    <span class="signed-out-tab-flash">You signed out in another tab or window. <a href="">Reload</a> to refresh your session.</span>
  </div>
  <div class="facebox" id="facebox" style="display:none;">
  <div class="facebox-popup">
    <div class="facebox-content" role="dialog" aria-labelledby="facebox-header" aria-describedby="facebox-description">
    </div>
    <button type="button" class="facebox-close js-facebox-close" aria-label="Close modal">
      <svg aria-hidden="true" class="octicon octicon-x" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48z"/></svg>
    </button>
  </div>
</div>


  </body>
</html>

