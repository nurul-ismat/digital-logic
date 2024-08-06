# Digital-Logic Design Project Description:
# 4-Bits Xerox Machine
Using the DEEDS simulator the Xerox machine controller, implemented on a single PLD (Programmable Logic Device) device, comprises a count-up counter, comparator, input switches, and a clock enabler. 
The input switches allow users to set the desired number of copies, which is then compared to the current count by the comparator. 
The count-up counter tracks the number of copies made and sends this count to the comparator until it matches the user input. 
The clock enabler/disabler controls the counter's operation, stopping or saturating it based on whether the comparator's conditions and the start button state are met.
