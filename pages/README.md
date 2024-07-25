## About

This study (Shank3ZZ) utilizes an autism mouse model, Shank3e21-/-, to investigate sex-specific effects in sleep architecture and homeostatic sleep response. This dataset contains polysomnography recordings conducted in a total of 28 adult male and female mice. Recordings are a total of 48 hours and cover 24 hours of baseline, followed by five hours of sleep deprivation and 19 hours of recovery sleep. All data were manually scored via visual inspection as one of three states: non-rapid eye movement sleep, rapid eye movement sleep, or wake. 

## Methods

Heterzygous Shank3e21-/- and wildtype breeding pairs were established to obtain wildtype (WT) and homozygous Shank3e21-/- littermates. Adult (8-12 week old) male and female mice were used. 

A total of 28 animals were used for surgical procedures. Adult (8-12 weeks old) male and female mice (n = 7 per sex and genotype) were anesthetized and stereotaxically implanted with four electroencephalographic (EEG) and two electromyographic (EMG) electrodes for assessment of sleep-wake behavior as previously described (Medina et al., 2022). Animals were subcutaneously given dexamethasone (1 mg/kg), enrofloxacin (5 mg/kg) and carprofen (5 mg/kg) prior to surgical procedure and for an additional 2 days after surgical procedures for a total of 72 hours. Buprenorphine (0.1/mg/kg) was given following righting after surgical procedures. Briefly, four stainless steel screws (BC‐002MP188, Bellcan International Corp, Hialeah, FL) were placed bilaterally over frontal (two) and parietal (two) cortices, and EMG electrodes were inserted bilaterally into the nuchal muscles. EEG electrode placement was secured with dental cement, the mice were individually housed and allowed a minimum of five days of recovery from surgery prior to habituation to the recording environment. Animals were connected to a lightweight, flexible tether and allowed five days to habituate to the tether and recording environment. After habituation, mice underwent 24 hours of undisturbed baseline recordings. Recordings started at lights on (ZT 1, day 1) and ended at lights on after a total of 48 hours of recordings. The first 24 hours consisted of baseline recording, followed by five hours of sleep deprivation at the beginning of lights on (ZT 1,  day 2). Sleep deprivation was followed by 19 hours of undisturbed recovery sleep. Sleep deprivation was conducted manually via gently handing, when necessary, animals were gently stroked with a soft brush to ensure animals remained awake. 

EEG and EMG data were collected using custom built electrophysiological amplifiers (IntanTechnologies, RHD amplifier chips) via a lightweight counterbalanced cable. 

Data was manually scored via visual inspection in 4 second resolution (epochs) by an experimenter blinded to conditions. Every epoch was scored as one of three states via the EEG and the Fast Fourier Transform (FFT): wake, non-rapid eye movement sleep (NREM), or rapid eye movement sleep (REMS). 

## Data overview

The [EDF files](:files_path:/EDF_Files) contain the raw data which include 2 EEG channels, and 1 EMG channel.  Data was converted from a proprietary digital format (.rhd) to European Data Format (.edf) file using custom software and digitized at 250 Hz. Data was then further analyzed and scored using VitalRecorder acquisition software (SleepSign for Animal, Kissei Comtec Co., LTD, Nagano, Japan). EEG and EMG data were high and low band pass filtered at 0.05 and 50 Hz and 15 and 30 Hz, respectively with a Notch filter set to 60 Hz.EEG power analysis was conducted from EEG spectra analysis of 0.5 - 50 Hz. The [CSV files](:files_path:/CSV_Files) provided contain scored every scored epoch along with spectral information for the entire 48 hours. 

The [Shank3ZZ_Annotated_DataCollectionForm (XLSX) file](:files_path:/) provides contextual information about the mice and EDF/CSV filenames.

## Access and usage restrictions

The Shank3ZZ dataset is only available for non-commercial use.

## Citation and acknowledgement

When using this dataset, users must cite the following:

>[Zhang GQ, Cui L, Mueller R, Tao S, Kim M, Rueschman M, Mariani S, Mobley D, Redline S. The National Sleep Research Resource: towards a sleep data commons. J Am Med Inform Assoc. 2018 Oct 1;25(10):1351-1358. doi: 10.1093/jamia/ocy064. PMID: 29860441; PMCID: PMC6188513.](https://pubmed.ncbi.nlm.nih.gov/29860441/)

Users must include the following text in any Acknowledgements:

> The Shank3ZZ work was supported by the National Institute of Neurological Disorders and Stroke (1F99NS135815) and the Simons Foundation Autism Research Initiative (Pilot Award 878115). The National Sleep Research Resource was supported by the U.S. National Institutes of Health, National Heart Lung and Blood Institute (R24 HL114473, 75N92019R002).

## Changelog

*July 2024*

- Make Shank3ZZ dataset available for data requests

## References

- Shank3ZZ GitHub Documentation: https://github.com/nsrr/shank3zz-documentation

## Questions?

Please reach out to us at support@sleepdata.org or in the [Forum](https://sleepdata.org/forum) if you have questions.
