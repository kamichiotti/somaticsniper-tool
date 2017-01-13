# somaticsniper-tool

Usage (--mapq, --dis_priors, --gor, --loh, --use_priop are all required at this time):
cwltool somatic_sniper.cwl.yaml --tumor /PATH/TO/<tumour_exome.bam> --normal /PATH/TO/<normal_EXOME.bam> --reference Homo_sapiens_assembly19.fasta --mapq 0 --dis_priors --gor --loh  --use_priorp
