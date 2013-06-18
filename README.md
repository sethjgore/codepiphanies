frontdevmemories
================

Snippets that provdie exponential learning results from codepiphanies.


Every single link in the www is a function. Everything clickable, every animation, every damn el thing is a function.
Even the close button: 

  // clicking the work panels close button: the current work panel slides down and the section scales up again
  
  $closeWorkItem.on( 'click', function( event ) {
  
  $sectionWork.removeClass( 'bl-scale-down' );
  $workPanelsContainer.removeClass( 'bl-panel-items-show' );
  $workPanels.eq( currentWorkPanel ).removeClass( 'bl-show-work' );
  
  return false;
  
  } );
