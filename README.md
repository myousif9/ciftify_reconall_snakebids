ciftify_reconall_snakebids
============

Snakebids wrapper for running ciftify recon-all

### example:
```
python run.py /scratch/myousif9/snsx_inprogress/output/snsx_preprocess_ciftify/derivatives/fmriprep/sourcedata/freesurfer/ /scratch/myousif9/Software/ciftify_wrapper/test1 participant --profile cc-slurm
```

### run options:
```
(snakemake_venv) [myousif9@gra-login3 ciftify_reconall_snakebids]$ python run.py --help
usage: run.py [-h] [--pybidsdb-dir PYBIDSDB_DIR] [--reset-db] [--force-output] [--help-snakemake]
              [--participant_label PARTICIPANT_LABEL [PARTICIPANT_LABEL ...]]
              [--exclude-participant-label EXCLUDE_PARTICIPANT_LABEL [EXCLUDE_PARTICIPANT_LABEL ...]]
              [--derivatives DERIVATIVES [DERIVATIVES ...]] [--fs-license FS_LICENSE]
              [--ciftify-opts CIFTIFY_OPTS [CIFTIFY_OPTS ...]]
              [--filter-t1 FILTER_T1 [FILTER_T1 ...]]
              [--wildcards-t1 WILDCARDS_T1 [WILDCARDS_T1 ...]] [--path-t1 PATH_T1]
              bids_dir output_dir {participant}
```