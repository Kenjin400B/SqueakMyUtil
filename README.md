# SqueakMyUtil
changes colors of icons of halos to more black and white  part of Black  Code Book Project

what?  change colors in squeak halos
when?  anytime
where?  look at the methodName below 
who?  for all
why?    sometimes like windows to more black colors and some white as well.   Part of the black code book project.  

Also if you want to customize to what you want.   its nice to see how the squeak team laid this out.

So to test you need to load the icon  halo type in the preferences  under halo   .   hit load to make it happen it should.  




!Preferences class methodsFor: 'prefs - halos' stamp: 'aa 3/16/2021 16:25' prior: 40648265!
iconicHaloSpecifications
	"Answer an array that characterizes the locations, colors, icons, and selectors of the halo handles that may be used in the iconic halo scheme"
      " Alex here"
	"Preferences resetHaloSpecifications"

	^ #(
	"  	selector				horiz		vert			color info						icon key
		---------				------		-----------		-------------------------------		---------------"
	(addCollapseHandle:		left			topCenter		(white)							'Halo-Collapse')
	(addPoohHandle:			right		center			(white)							'Halo-Pooh')
	(addDebugHandle:		right		topCenter		(black	lighter )		'Halo-Debug')
	(addDismissHandle:		left			top				(white		muchLighter)			'Halo-Dismiss')
	(addRotateHandle:		left			bottom			(white)							'Halo-Rot')
	(addMenuHandle:		leftCenter	top				(white)							'Halo-Menu')
	(addTileHandle:			left			bottomCenter	(white)					'Halo-Tile')
	(addViewHandle:			left			center			(white)							'Halo-View')
	(addGrabHandle:			center		top				(black)							'Halo-Grab')
	(addDragHandle:			rightCenter	top				(black)							'Halo-Drag')
	(addDupHandle:			right		top				(white)							'Halo-Dup')	
	(addMakeSiblingHandle:	right		top				(black)				'Halo-Dup')	
	(addHelpHandle:			center		bottom			(black)						'Halo-Help')
	(addGrowHandle:		right		bottom			(black)						'Halo-Scale')
	(addScaleHandle:		right		bottom			(black)					'Halo-Scale')
	(addScriptHandle:		rightCenter	bottom			(black)			'Halo-Script')
	(addPaintBgdHandle:		right		center			(white)						'Halo-Paint')
	(addViewingHandle:		leftCenter	bottom			(white lighter)				'Halo-View')
	(addRepaintHandle:		right		center			(white)						'Halo-Paint')
	(addFontSizeHandle:		leftCenter	bottom			(white)						'Halo-FontSize')
	(addFontStyleHandle:		center		bottom			(lightRed)						'Halo-FontStyle')
	(addFontEmphHandle:	rightCenter	bottom			(lightBrown darker)				'Halo-FontEmph')
	(addRecolorHandle:		right		bottomCenter	(magenta darker)				'Halo-Recolor')
	(addChooseGraphicHandle:	right	bottomCenter	(green muchLighter)			'Halo-ChooseGraphic')
		) ! !
