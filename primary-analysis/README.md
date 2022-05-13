# primary-analysis

We perform primary analysis independently for each experiment (see `transcriptional-recording-gut-metadata.txt`).

We provide the following files for `experiment-type`:
1. `Snakemake` and `config.yml` for Record-seq
2. `Snakemake` and `config.yml`for RNA-seq
3. `Snakemake` and `config.yml` multiplexed Record-seq

In addition to this, we also have the `primary-analysis-metadata.txt` file which lists the reference genome and plasmid for each experiment. The genome and plasmid references are in the `resources` folder. For each Record-seq experiment, the `primary-analysis-metadata.txt` file also lists a unique library barcode (LBC). These parameters need to be changed in the `config.yml` file prior to running primary analysis for each experiment.

The configuration of the environment and directory structure should be done as per the instructions in [this repository](https://github.com/plattlab/Transcriptional-Recording). 
