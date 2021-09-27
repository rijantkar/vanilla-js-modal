# vanilla-js-modal

* Create html structure
    * create a button to open/close button, have an data set
    * modal, modal header, modal body - use &times; for close button with an data set
    * seperate div overlay [have and id]
* Create css
    * modal/overlay with fixed position
    * center modal by top/left 50%
    * use transform translate -50%, -50% with scale 0
      * use translate with scale as 1 for modal active
    * z-index of modal to be higher
    * add transition to modal/overlay
    * opacity to overlay/overlay active as 0 and 1
    * pointer events to none for overlay and all for overlay active
* Create javascript
    * target modalTargets/closeButtons using dataset
    * get overlay button
    * foreach of dataset above to open/close modal
    * open to add active class
    * close to remove active class
    * add listener to overlay to remove closet .modal 
