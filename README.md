adapt-menu-singlePageCourse
=====================

Enables the use of a single page course without a menu calls the first contentOjects page id

Your theme must contain a class for 

.display-none{
  display: hidden;
  }
  
This removes the nav bar, should you wish to bring it back in for pageProgress or Resources you will need to amend/remove the .padding-none class used to bring the title bar to the top of the screen in adapt-menu-singlePageCourse.less

.padding-none {
	padding-top: 0px !important;
	padding-bottom: 0px;
}

should you need to hide other nav bar element such as drawer or the nav bar itself (back is hidden by this plugin) you need to reflect this in your theme though remember some plugins like page progress and tutor require a nav bar i.e.

  .navigation-drawer-toggle-button{
    display: hidden;
  }
  .navigation{
    display: hidden;
  }
  wrappers{
	padding-top: 0px !important;
	padding-bottom: 0px;
  }
