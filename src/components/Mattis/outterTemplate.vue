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
                <div class="row row-offcanvas row-offcanvas-left" data-sticky-wrap="" style="min-height: 775px;">
                    <div class="col-md-3 col-lg-2 sidebar sidebar-offcanvas" id="sidebar">
                        <ul class="side-nav list-unstyled">
                            <li class="header"><i class="fa fa-heart mr-2"></i> Character</li>
                            <li class="user-name"><span class="display-user"><a href="https://toyhou.se/technibabble"><img src="/img/file.toyhou.se/file.toyhou.se=users=technibabble3" class="display-user-avatar"><span class="display-user-username">technibabble</span></a></span></li>
                            <li class="character-folder subheader">
                                <a href="https://toyhou.se/technibabble/characters/folder:unsorted">
                                <i class="fi-folder sidebar-icon"></i>Unsorted
                                </a>
                            </li>
                            <li class="character-name">
                                <span class="display-character"><a href="/2313436.tightly-packed"><img src="/img/file.toyhou.se/file.toyhou.se=characters=23134361528844141" class="mr-2">Tightly Packed</a></span>
                            </li>
                            <li class="divider sidebar-divider-collections">
                            <li class=" sidebar-li-gallery">
                                <a href="https://toyhou.se/2313436.tightly-packed/gallery">
                                <i class="far fa-image fa-fw sidebar-icon"></i>Gallery
                                </a>
                            </li>
                            <li class=" sidebar-li-library">
                                <a href="https://toyhou.se/2313436.tightly-packed/literatures">
                                <i class="fa fa-book fa-fw sidebar-icon"></i>Library
                                </a>
                            </li>
                            <li class=" sidebar-li-worlds">
                                <a href="https://toyhou.se/2313436.tightly-packed/worlds">
                                <i class="fa fa-globe fa-fw sidebar-icon"></i>Worlds
                                </a>
                            </li>
                            <li class=" sidebar-li-links">
                                <a href="https://toyhou.se/2313436.tightly-packed/links">
                                <i class="fa fa-link fa-fw sidebar-icon"></i>Links
                                </a>
                            </li>
                            <li class="divider sidebar-divider-interactions">
                            <li class="  sidebar-li-comments">
                                <a href="https://toyhou.se/2313436.tightly-packed/comments">
                                <i class="fa fa-comment fa-fw sidebar-icon"></i>Comments
                                </a>
                            </li>
                            <li class="divider sidebar-divider-ownership">
                            <li class=" sidebar-li-ownership">
                                <a href="https://toyhou.se/2313436.tightly-packed/ownership">
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
                                        <img src="/img/file.toyhou.se/file.toyhou.se=characters=23134361528844141" class="profile-name-icon">
                                    </div>
                                    <div class="profile-name-info">
                                        <h1 class="display-4">Tightly Packed</h1>
                                        <h2><span class="display-user"><a href="https://toyhou.se/technibabble"><i class="fi-torso user-name-icon"></i>technibabble</a></span></h2>
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
                                                <div class="profile-stats-content  col-12">
                                                    <dl class="fields">
                                                        <div class="row fields-field">
                                                            <dt class="field-title col-sm-4">
                                                                Created
                                                            </dt>
                                                            <dd class="field-value col-sm-8">
                                                                <abbr class="tooltipster datetime" title="" data-original-title="12 Jun 2018, 3:55:28 pm">1 year, 10 months ago</abbr>
                                                            </dd>
                                                        </div>
                                                        <div class="row fields-field">
                                                            <dt class="field-title col-sm-4">
                                                                Creator
                                                            </dt>
                                                            <dd class="field-value col-sm-8">
                                                                <span class="display-user"><a href="https://toyhou.se/technibabble"><i class="fi-torso user-name-icon"></i>technibabble</a></span>
                                                            </dd>
                                                        </div>
                                                        <div class="row fields-field">
                                                            <dt class="field-title col-sm-4">
                                                                Favorites
                                                            </dt>
                                                            <dd class="field-value col-sm-8">
                                                                <a href="/2313436.tightly-packed/favorites" th-modal-trigger="">217</a>
                                                            </dd>
                                                        </div>
                                                    </dl>
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
                                    <div class="card-inverse card-primary text-center py-2 px-4 mb-4" style="margin-top:-17px;">
                                        <h1 class="display-4 mb-2 d-flex justify-content-around" style="font-variant:small-caps;">
                                            <i class="fal fa-star my-auto"></i> Tightly Packed <i class="fal fa-star my-auto"></i>
                                        </h1>
                                        <div class="row">
                                            <div class="col-md-4">
                                                <a class="btn btn-secondary btn-block rounded-0 border-0 mb-2" href="/~forums/16.htmlcss-graphics/69092">
                                                <i class="fal fa-comments-alt"></i> Thread
                                                </a>
                                            </div>
                                            <div class="col-md-4">
                                                <a class="btn btn-secondary btn-block rounded-0 border-0 mb-2" href="/3200414.get-code/3204512.tightly-packed?key=bkUVhqQjsdxKEa4" target="_blank">
                                                <i class="far fa-code"></i> <strong>Code</strong>
                                                </a>
                                            </div>
                                            <div class="col-md-4">
                                                <a class="btn btn-secondary btn-block rounded-0 border-0 mb-2" href="/technibabble">
                                                <i class="fal fa-home"></i> Home
                                                </a>
                                            </div>
                                        </div>
                                    </div>

                                    <mattis></mattis>
                                    <div class="float-right"><a href="/technibabble" title="" data-placement="left" class="btn btn-outline-primary d-inline-flex p-2 rounded-circle tooltipster" data-original-title="code|techni"><i class="fal fa-code m-auto"></i></a></div>
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
                    <span class="mx-1">633 Users Online</span>
                    <span class="mx-1">10:56 am</span>
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
        import Mattis from './mattis.vue';
        export default {
            components: {
                Mattis
            }
        }
    </script>
<style src="./style.css" lang="css" scoped></style>
