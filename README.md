# user-stories-quantum-cards

As a Trixel user, I want to be able to select a Trixelation to turn it into a Quantum Card.
*	Mostly Covered
*	No flow yet for native entry into creation as opposed to entry through a trixelation’s feed menu.
 
Putting the stats on the card as opposed to a form. Text boxes w/defaults.
*	Involves
  *	Text boxes on top of the card should be transparent as to allow just the text to show, not the box itself.
  *	This is a preview mode.
 
Submit card for purpose of printing
*	What’s involved
  *	Let Bill gather thoughts.
  *	Create page for printing form to live in 
    *	Dropdown?
  *	Create the form in polymer with all info from Bill with validation 
    *	read on polymer validation
  *	build the javascript object to be sent with order info
  *	app-ajax to do http PUT to url api.trixel.io./user/orders/stickersheet/{trid}
  *	grab response in callback
  *	display response information to user
  *	confirmation email? (may be serverside’s job)
*	Problems
  *	like all of it
  *	read up on core ajax
 
Saving/storing quantum cards, potentially as WIPs.
*	Involves
  *	Similar to the process for how people save trixelations as WIPs
*	Problems
  *	Doesn’t seem to use ajax to save
    *	Have to do more digging to determine this.  Looks like it was accomplished using local functions in trixel-create.

 
Flow for someone already in the Quantumverse who wants to make a card?


