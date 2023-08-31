# PyLabRobot Examples
This repo provides Jupyter notebooks of PyLabRobot example code


## Simulator notebooks
These notebooks can be run in the simulator

* [Saving decks](saving_deck)

* [Well indexing](Indexing_Resources.ipynb)

## Tutorial Walkthrough
Run `pip install pylabrobot[simulation]` from the command line

### Creating a deck in the GUI
1. Run `plr-gui` from the command line in the folder you would like to save a deck 

### Saving a deck in a script
1. Run `jupyter notebook`
2. Navigate to `pylabrobot_examples/saving_deck/save_deck.ipynb`
3. Run the cells up to `lh.deck.save('save_deck.json')`

# To-do
## Simulator notebooks
* Worklists
* Moving labware
* Plate patterns
* Liquid handling parameters (flowrate, air blowout, air transport)
* Error handling
* Robot decks
    * OT-2
    * Tecan EVO
    * Hamilton STAR
* Volume tracking
* Composition modeling

## Robot-specific notebooks
These notebooks provide example code that is specific to a particular robot

### Hamilton STAR
* TADM curves
