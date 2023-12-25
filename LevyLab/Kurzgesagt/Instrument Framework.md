Clone the Instrument Framework Template
Add .vipb to gitignore
Checkout a develop branch
Run the RunMe VI to configure the Name and Icon
Delete the RunMe file once it's done

{In the new instrument framework, we should manually add the applauncher into the documentation}

Then we should configure the overrides.
First is the name. Go to the child of name. select the parent method and press Ctrl+Space and Ctrl+R to automatically delete and rewire
then manually add a constant name for the SMO name.
Then the port. Go to the parent method. Add a port to github doc.
add the same port to the port override