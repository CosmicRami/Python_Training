# READ ME FIRST #

## Pulsar Profile Analysis Tool (P-PAT) ##

This package (Pulsar_Profile_Analysis_Tool') is used to determine any variablilities in the pulsar's profile by comparing each observations pulsar profile over multiple epochs as a time series and looking for any variations over this time.

These variations are plotted as profile residuals as a function of time to showcase how the pulsar's profile changes over time.

### Installation ###

```
pip install PPAT
```
### Running this Script ###
The script runs by performing a number of chronological functions. These include:

1. Downloading and converting the file to ASCII format from PSRCHIVE format
2. Loading in the tezt file and reading in the columns
3. Running a loop over the archive to perform step 1 for each loop
4. Using the intesity of the profile to normalise the profile with the max peak, using np.argmax
5. Measuring the diff between the normalised observation file and the template
6. Recording this difference as the residual in a file

### Script ###
```
The script will go in here
```

### Credit ###
Please credit this work by citing the following link: Mandow et al. 2023, ApJ, 455, 16 <link>
