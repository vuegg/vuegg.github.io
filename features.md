# Features
---

## Current Features

* Mockup / prototype by drag'n'drop components and move/resize them
* Support for standard Mouse and Keyboard combinations
* Responsive preview (phone, tablet, web)
* Basic set of HTML5 elements
* Material design components ([vue-mdc-adapter](https://github.com/stasson/vue-mdc-adapter))
* [Vuejs](https://github.com/vuejs/vue) sources generation (download .zip)
* Connect with GitHub (save/load vuegg projects)
* Local persistence to save the work in progress
* ... more to come with time

</br>

## Keyboard Shortcuts

### Selection
* **Mouse down + Drag + Mouse up**: Draw a selection area
* **Ctrl [or Meta] + Click**: Select outer-most item, or parent container
* **Ctrl [or Meta] + Shift + Click**: Add [outer-most] item to selection
* **Esc**: Clear selection

### Undo / Redo
* **Ctrl [or Meta] + Z**: Undo last action
* **Ctrl [or Meta] + Shift + Z**: Redo last action

### Copy / Cut / paste
* **Ctrl [or Meta] + C**: Copy selection
* **Ctrl [or Meta] + X**: Cut selection
* **Ctrl [or Meta] + V**: paste selection

### Delete
* **Delete [or Backspace]**: Deletes selection

</br>

## Roadmap

Off the top of my head, I foresee the following features to be developed for the next releases:

- [ ] Hold shift to maintain aspect ratio on manual resize
- [ ] Ability to zoom-in / zoom-out in the editor
- [ ] Allow the insertion of raw CSS rules (expert mode)
  - [ ] Identify possible risks
- [ ] Add extra styles controls
  - [ ] BoxShadow
  - [ ] Overflow
  - [ ] TextOverflow
- [ ] Manage creation/edition of custom components
  - [ ] Transition to custom component (group/ungroup)
  - [ ] Implement custom component editor view
- [ ] Implement tree navigator to visualize page structure
