# Molecule testing

Create a new role with molecule:
	
	molecule init role myrole

Then test it:

	molecule test

And test it but leacve the container running for debugging:

	molecule converge

Set a 'brakepoint' uning `fails:` in the tasks