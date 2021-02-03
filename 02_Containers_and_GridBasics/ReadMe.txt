Containers
---------------
Containers are a fundamental building block of Bootstrap that contain, pad, and align your content within a given device or viewport.

Bootstrap comes with three different containers:

    .container, which sets a max-width at each responsive breakpoint
    .container-fluid, which is width: 100% at all breakpoints
    .container-{breakpoint}, which is width: 100% until the specified breakpoint

Breakpoints :
Bootstrap includes six default breakpoints, sometimes referred to as grid tiers, for building responsively

Breakpoint           	Class infix 	        Dimensions
X-Small 	              None 	                    <576px
Small 	                   sm 	                     ≥576px
Medium 	                   md 	                     ≥768px
Large 	                  lg 	                     ≥992px
Extra large 	          xl 	                     ≥1200px
Extra extra large 	      xxl 	                     ≥1400px

                                                                                                                                                   
                Extra   Small   Medium  Large    X-Large XX-Large
                small   ≥576px  ≥768px   ≥992px  ≥1200px  ≥1400px
                <576px                                                                                                                 
.container 	    100% 	540px 	720px 	960px 	1140px 	1320px
.container-sm 	100% 	540px 	720px 	960px 	1140px 	1320px
.container-md 	100% 	100% 	720px 	960px 	1140px 	1320px
.container-lg 	100% 	100% 	100% 	960px 	1140px 	1320px
.container-xl 	100% 	100% 	100% 	100% 	1140px 	1320px
.container-xxl 	100% 	100% 	100% 	100% 	100% 	1320px
.container-fluid 100% 	100% 	100% 	100% 	100% 	100%



Grid System
.Bootstrap's grid system is built with flexbox and allows up to 12 columns across the page.
.The grid system is responsive, and the columns will re-arrange automatically depending on the screen size.
.Make sure that the sum adds up to 12 or fewer (it is not required that you use all 12 available columns).

Grid Classes

The Bootstrap 4 grid system has five classes:
    .col- (extra small devices - screen width less than 576px)
    .col-sm- (small devices - screen width equal to or greater than 576px)
    .col-md- (medium devices - screen width equal to or greater than 768px)
    .col-lg- (large devices - screen width equal to or greater than 992px)
    .col-xl- (xlarge devices - screen width equal to or greater than 1200px)












