# PyLabRobot Examples
This repo provides Jupyter notebooks of PyLabRobot example code


## Simulator notebooks
These notebooks can be run in the simulator

* [Saving decks](saving_deck)

* [Well indexing](Indexing_Resources.ipynb)

## Tutorial Walkthrough
1. Run `pip install pylabrobot[simulation]` from the command line
2. Run `jupyter notebook`
3. Navigate to `pylabrobot_examples/saving_deck/save_deck.ipynb`
4. Run the cells up to `lh.deck.save('save_deck.json')`

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
