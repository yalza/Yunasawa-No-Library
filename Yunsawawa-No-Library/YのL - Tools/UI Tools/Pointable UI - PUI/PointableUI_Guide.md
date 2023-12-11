<h1 align="center"> YのL Tools - Pointable UI (PUI) </h1>

<h4 align="center"> A better solution for Unity's Button with more features and advantages. <br><br>

## Description
A better version of Unity's Button:
- Have more individual modes for different purposes.
- Familiar usage due to some properties are the same with Unity's button.

## Usage Guide

<h3><i> PUI - Graphic </i></h3>
<b><i> Usage: </i></b> Change, switch PUI graphic with familiar properties.

<b><i> Properties: </i></b>

<details> 
  <sumary><b> Transition: Color Tint </b></sumary>

  <p align="center">
    <img width="100%" alt="TransitionColorTint" src="https://github.com/Yunasawa/Yunasawa-No-Library/assets/113672166/d140a057-7bf8-411c-8e90-ab1edbad45bb">
  </p>
</details>

<details>
 <summary><b>Toggles</b></summary>
  
 <p align="center">
   <img width="915" alt="chrome_aClIcjH3wq" src="https://user-images.githubusercontent.com/31889435/226558578-78287342-711c-4b4b-acf3-18b316f3216b.gif">
   <img width="915" alt="chrome_aClIcjH3wq" src="https://user-images.githubusercontent.com/31889435/226493660-ba63cb16-a046-48f3-8d1a-c1ea0007de4a.png">
 </p>

  Toggles will simply display the state of the instance, can be clicked to toggle the instance active state.

  ```
  Show Active Toggles     Enable the toggles.
  Active Swiping          Click and drag over check boxes to toggle them.
  Swipe Same State        Only toggle the instances with the same state as the first selected.
  Swipe Selection Only    If a selection exists, only toggle the selected instances.
  Depth Mode              The accepted criteria for selecting instances when swiping.
  ```
</details>

Transition: Sprite Swap
- Target Graphic: Image component of object.
- Normal Sprite: Sprite of Target Graphic when PUI is idle.
- Highlighted Sprite: Sprite of Target Graphic when pointer enter PUI.
- Pressed Sprite: Sprite of Target Graphic when PUI is pressed.
- Selected Sprite: Sprite of Target Graphic when PUI is selected.
- Disabled Sprite: Sprite of Target Graphic when PUI is not Interactable.

<p align="center"><img width="100%" alt="TransitionColorTint" src="https://github.com/Yunasawa/Yunasawa-No-Library/assets/113672166/fe2ad6c5-e18b-4ae6-ae30-8725d076ec64"></p>

Transition: Animation
- Normal Trigger: Animation played when PUI is idle.
- Highlighted Trigger: Animation played when pointer enter PUI.
- Pressed Trigger: Animation played when PUI is pressed.
- Selected Trigger: Animation played when PUI is selected.
- Disabled Trigger: Animation played when PUI is not Interactable.

<p align="center"><img width="100%" alt="TransitionColorTint" src="https://github.com/Yunasawa/Yunasawa-No-Library/assets/113672166/65a52cd5-7b43-40e6-af39-5b0c2b17d7e2"></p>

<h3><i> PUI - Event </i></h3>

- OnSelect: Invoked when PUI is selected.
- OnDeselect: Invoked when PUI is deselected.
- OnPointerClick: Invoked when PUI is clicked then released, but not works when pointer is out of PUI.
- OnPointerDown: Invoked when PUI is pressed.
- OnPointerUp: Invoked when PUI is released, still works when pointer is out of PUI.
- OnEnter: Invoked when pointer enter PUI.
- OnExit: Invoked when pointer exit PUI;

<p align="center"><img width="100%" alt="TransitionColorTint" src="https://github.com/Yunasawa/Yunasawa-No-Library/assets/113672166/0484cc5c-0f3b-401a-ad9a-a094259a3a96"></p>



<h3><i> PUI - Event </i></h3>
