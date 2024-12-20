Are you wondering why you don't have wifi?

Try the following:

1. Open a terminal and check to see if you have a connection with IWD, to do so, do the following:

	a. Open COSMIC Terminal
	b. Type "sudo iwctl"
	c. station [insert device name] scan
		ex. station wlan0 scan
	d. Try and connect to your wifi network via:
		i. station [insert device name] connect [insert lan]
			ex. station wlan0 connect [my network name]
	e. exit out with "exit" and ping acreetionos-linux.github.io

If this doesn't work, make an issue over on the acreetionos linux github! We are happy to try and help. Make sure to do it under the *AcreetionOS* repo.

