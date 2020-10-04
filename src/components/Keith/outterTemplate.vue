<template>
    <div id="container" class="page-container page-container-character">
        <a id="top"></a>
        <nav class="navbar navbar-toggleable-sm navbar-inverse header" data-topbar="" role="navigation" id="header">
            <button class="navbar-toggler navbar-toggler-right" type="button" data-toggle="collapse" data-target="#headerContent" aria-controls="headerContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
            </button>
            <a class="navbar-brand" href="https://toyhou.se">TOYHOU.SE</a>
            <div class="collapse navbar-collapse" id="headerContent">
                <div class="mr-auto"></div>
                <ul class="navbar-nav navbar-right">
                    <li class="nav-item"><a class="nav-link" href="https://toyhou.se/~account/register">Register</a></li>
                    <li class="nav-item"><a class="nav-link" href="#" data-toggle="modal" data-target="#modal-login">Login</a></li>
                </ul>
            </div>
        </nav>
        <div class="hidden-md-up nav-mobile-menu">
            <button class="btn btn-outline-secondary nav-mobile-menu-toggle" data-toggle="offcanvas" data-target="#">
            Menu <span class="fa fa-caret-right" style=""></span>
            </button>
        </div>
        <div id="main" class="clearfix container-fluid main-container full-sidebar">
            <div class="row row-offcanvas row-offcanvas-left" data-sticky-wrap="" style="min-height: 504px;">
                <div class="col-md-3 col-lg-2 sidebar sidebar-offcanvas" id="sidebar">
                    <ul class="side-nav list-unstyled">
                        <li class="header"><i class="fa fa-heart mr-2"></i> Character</li>
                        <li class="user-name"><span class="display-user"><a href="https://toyhou.se/Hukiolukio"><img src="https://f2.toyhou.se/file/f2-toyhou-se/users/Hukiolukio?14" class="display-user-avatar"><span class="display-user-username">Hukiolukio</span></a></span></li>
                        <li class="character-folder subheader">
                            <a href="https://toyhou.se/Hukiolukio/characters/folder:1264054"><i class="mr-1 fa fa-folder"></i>Large Profiles</a>
                        </li>
                        <li class="character-name">
                            <span class="display-character"><a href="/6545504.tabbed-profile"><img src="https://f2.toyhou.se/file/f2-toyhou-se/characters/6545504?1586559569" class="mr-2">Tabbed Profile</a></span>
                        </li>
                        <li class="divider sidebar-divider-collections"></li>
                        <li class=" sidebar-li-gallery">
                            <a href="https://toyhou.se/6545504.tabbed-profile/gallery">
                            <i class="far fa-image fa-fw sidebar-icon"></i>Gallery
                            </a>
                        </li>
                        <li class=" sidebar-li-library">
                            <a href="https://toyhou.se/6545504.tabbed-profile/literatures">
                            <i class="fa fa-book fa-fw sidebar-icon"></i>Library
                            </a>
                        </li>
                        <li class=" sidebar-li-worlds">
                            <a href="https://toyhou.se/6545504.tabbed-profile/worlds">
                            <i class="fa fa-globe fa-fw sidebar-icon"></i>Worlds
                            </a>
                        </li>
                        <li class=" sidebar-li-links">
                            <a href="https://toyhou.se/6545504.tabbed-profile/links">
                            <i class="fa fa-link fa-fw sidebar-icon"></i>Links
                            </a>
                        </li>
                        <li class="divider sidebar-divider-interactions"></li>
                        <li class="  sidebar-li-comments">
                            <a href="https://toyhou.se/6545504.tabbed-profile/comments">
                            <i class="fa fa-comment fa-fw sidebar-icon"></i>Comments
                            <span class="pull-right sidebar-stat sidebar-stat-coments">9</span>
                            </a>
                        </li>
                        <li class="divider sidebar-divider-ownership"></li>
                        <li class=" sidebar-li-ownership">
                            <a href="https://toyhou.se/6545504.tabbed-profile/ownership">
                            <i class="far fa-check-square fa-fw sidebar-icon"></i>Ownership
                            </a>
                        </li>
                    </ul>
                </div>
                <div class="col-sm-12 col-md-9 col-lg-10 content-main" id="content">
                    <div class="character-profile">
                        <div class="row profile-header">
                            <div class="col-lg-6 col-12 profile-section profile-name-section">
                                <div class="img-thumbnail">
                                    <img src="https://f2.toyhou.se/file/f2-toyhou-se/characters/6545504?1586559569" class="profile-name-icon">
                                </div>
                                <div class="profile-name-info">
                                    <h1 class="display-4">Tabbed Profile</h1>
                                    <h2><span class="display-user"><a href="https://toyhou.se/Hukiolukio"><i class="fi-torso user-name-icon"></i>Hukiolukio</a></span></h2>
                                </div>
                            </div>
                            <div class="col-lg-6 col-12 profile-section profile-info-section">
                                <div class="card">
                                    <div class="card-block bg-faded">
                                        <div class="profile-info-title hidden-lg-up">
                                            <h2>Info</h2>
                                            <hr>
                                        </div>
                                        <div class="profile-info-content row">
                                            <div class="profile-stats-content col-lg-8 col-md-6 col-12">
                                                <dl class="fields">
                                                    <div class="row fields-field">
                                                        <dt class="field-title col-sm-4">
                                                            Created
                                                        </dt>
                                                        <dd class="field-value col-sm-8">
                                                            <abbr class="tooltipster datetime" title="" data-original-title="10 Apr 2020, 3:59:26 pm">5 months, 24 days ago</abbr>
                                                        </dd>
                                                    </div>
                                                    <div class="row fields-field">
                                                        <dt class="field-title col-sm-4">
                                                            Creator
                                                        </dt>
                                                        <dd class="field-value col-sm-8">
                                                            <span class="display-user"><a href="https://toyhou.se/Hukiolukio"><i class="fi-torso user-name-icon"></i>Hukiolukio</a></span>
                                                        </dd>
                                                    </div>
                                                    <div class="row fields-field">
                                                        <dt class="field-title col-sm-4">
                                                            Favorites
                                                        </dt>
                                                        <dd class="field-value col-sm-8">
                                                            <a href="/6545504.tabbed-profile/favorites" th-modal-trigger="">416</a>
                                                        </dd>
                                                    </div>
                                                </dl>
                                            </div>
                                            <div class="col-lg-4 col-md-6 col-12 profile-tags-content">
                                                <a href="https://toyhou.se/Hukiolukio/characters/tagged:profile template" class="badge badge-primary badge-pill">profile template</a>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="profile-section profile-content-section ">
                            <div class="profile-content-title">
                                <h2>Profile</h2>
                                <hr>
                            </div>
                            <div class="profile-content-content user-content fr-view">
                                <div class="container mb-4">
                                    <div class="row justify-content-center">
                                        <div class="col-md-7 mb-4">
                                            <div class="card card-block bg-faded mb-2">
                                                <div class="card card-block">
                                                    <p class="display-4 text-primary font-weight-bold mb-2"><i class="far fa-cog"></i> Info and Rules</p>
                                                    <div class="bg-primary mb-2" style="height:2px;width:100%;"></div>
                                                    <ul class="list-unstyled text-primary">
                                                        <li class="mb-2">
                                                            <i class="far fa-arrow-right"></i>
                                                            this profile is free to use! no need to ask for permission to use it!
                                                        </li>
                                                        <li class="mb-2">
                                                            <i class="far fa-arrow-right"></i>
                                                            don't remove my credit, but you can move it
                                                        </li>
                                                        <li class="mb-2">
                                                            <i class="far fa-arrow-right"></i>
                                                            feel free to edit this profile however you like, but don't redistribute it
                                                        </li>
                                                        <li class="mb-0">
                                                            <i class="far fa-arrow-right"></i>
                                                            feel free to tell me if you use my profile, I love to see them in use!
                                                        </li>
                                                    </ul>
                                                </div>
                                            </div>
                                            <div class="row justify-content-between">
                                                <div class="col-md-4 mb-2"><a href="https://toyhou.se/~forums/16.htmlcss-graphics/39007.-free-html-templates-" class="btn btn-outline-primary btn-lg btn-block bg-faded shadow-none"><i class="far fa-list"></i> my thread</a></div>
                                                <div class="col-md-4 mb-2"><a href="https://pastebin.com/qN5N2Hxg" class="btn btn-primary btn-lg btn-block shadow-none"><i class="far fa-code"></i> the code</a></div>
                                                <div class="col-md-4 mb-2"><a href="https://ko-fi.com/hukiolukio" class="btn btn-outline-primary btn-lg btn-block bg-faded shadow-none"><i class="far fa-mug-hot"></i> tip me</a></div>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                                <keith></keith>
                            </div>
                        </div>
                        <div class="profile-section profile-gallery-section">
                            <div class="profile-gallery-title">
                                <h2>
                                    Recent Images
                                    <hr>
                                </h2>
                            </div>
                            <div class="profile-gallery-content">
                                <p class="image-gallery-none">No images.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div id="footer" class="text-muted text-center p-3 footer" data-sticky-footer="">
            <div>
                <span class="mx-1">851 Users Online</span>
                <span class="mx-1">4:18 pm</span>
                <span class="mx-1">© cyancrows 2017</span>
            </div>
            <div>
                <span class="mx-2"><a href="https://toyhou.se/~about">About</a></span>
                <span class="mx-2"><a href="https://toyhou.se/~faq/general">FAQ</a></span>
                <span class="mx-2"><a href="https://toyhou.se/~rules">Rules</a></span>
                <span class="mx-2"><a href="https://toyhou.se/~tos">TOS</a></span>
            </div>
        </div>
    </div>
</template>

<script>
    import Keith from './keith.vue';
    export default {
        components: {
            Keith
        }
    }
</script>
