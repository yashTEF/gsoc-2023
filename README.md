## Google Summer of Code 2023: Work Product
*Project Gist and relevant work done during the GSoC 2023 program*

## About The Project

**Eclipse Cargo Tracker: Improve Visual Appeal and User Experience**

Eclipse Cargo Tracker: [Project Website](https://eclipse-ee4j.github.io/cargotracker/) <br>
See this project on: [Google Summer of Code](https://summerofcode.withgoogle.com/projects/#5104569337511936) <br>
Mentor: [Reza Rahman](https://github.com/m-reza-rahman)

**Project Accomplished Milestones**

1. Improved design and structuring for the project website
2. Improved User Interface for the Cargo Tracker application with a more modern look.
3. Move to Primefaces version 12.0.0
4. Bug Fixes

## Improved design and structuring for the project website

The project website for the Eclipse Cargo Tracker project now has a improved look
with a better design and styling along with a modern-look navigation bar.

Links to code:
  1. [Project Website Improvements](https://github.com/eclipse-ee4j/cargotracker/pull/241)
  2. [Navbar and Scrollbar](https://github.com/eclipse-ee4j/cargotracker/pull/257)

## Improved User Interface for the Cargo Tracker application with a more modern look.

The Cargo Tracker application now has an improved and modern look.
This includes a better menu bar, addition of buttons for better navigation and a loading progress topbar.
Also includes better structuring and general styling for the application.

Link to code:
  [Improve UI](https://github.com/eclipse-ee4j/cargotracker/pull/260)

## Move to Primefaces version 12.0.0

The existing external dependency to Primefaces library was deprecated and old, so the below PR provides
a successful upgrade to the latest Primfaces Saga release with minimal bugs.

Link to code:
  [Primefaces 12.0.0](https://github.com/eclipse-ee4j/cargotracker/pull/269)

## Bug Fixing

The above improvements and upgrades brought with them bugs which needed addressing.

  1. Responsive Navbar
     Link to Issue: [Navbar Issue](https://github.com/eclipse-ee4j/cargotracker/issues/259) <br>
     Fix: [#262](https://github.com/eclipse-ee4j/cargotracker/pull/262)
     
  2. Live Map url not rendering
     Link to Issue: [Live Map Issue](https://github.com/eclipse-ee4j/cargotracker/issues/270) <br>
     Fix: [#271](https://github.com/eclipse-ee4j/cargotracker/pull/271)
     
  3. Change deadline date pick is too restrictive
     Link to Issue: [Restrictive deadline](https://github.com/eclipse-ee4j/cargotracker/issues/274) <br>
     Fix: [#277](https://github.com/eclipse-ee4j/cargotracker/pull/277)
     
  4. Event logger screen should be more mobile friendly
     Link to Issue: [Mobile friendly event logger](https://github.com/eclipse-ee4j/cargotracker/issues/275) <br>
     Fix:    
       1) [4a](https://github.com/eclipse-ee4j/cargotracker/pull/278)
     
       2) [4b](https://github.com/eclipse-ee4j/cargotracker/pull/279)
     
       3) [4c](https://github.com/eclipse-ee4j/cargotracker/pull/280)
     
       4) [4d](https://github.com/eclipse-ee4j/cargotracker/pull/281)
    

## Future Scope of Work
  The upgrade to latest primefaces brings with it opportunity to add components to the User Interface which
  supports modern tooling and rendering this could include improved panel grids, skeletons on loading
  ajax loading of widget, timeline events etc.
     

### Reach out<br> 

[Email](yashbharatiya@gmail.com) <br>

[Github](https://github.com/yashTEF)
