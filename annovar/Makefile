RVTESTS = /data/home/hhx779/software/rvtests/executable
GENES = GPR98,USH2A,DFNB31,CDH23,PCDH15,USH1C,MYO7A

VCFs = /data/WHRI-EndocrinePituitaryGroup/sherine/Exome78Vcfs/annovar


WES78.hg19_multianno.vcf: 
	${ANNOVAR}/table_annovar.pl CallsWES.vcf  ${ANNOVAR}/humandb/ -buildver hg19 -out WES78 -remove -protocol refGene,ensGene,cytoBand,exac03,avsnp147,\
	dbnsfp30a,clinvar_20170130,mitimpact2,gnomad_exome,revel,intervar_20170202 -operation g,g,f,f,f,f,f,f,f,f,f  -nastring . -vcfinput


S0969.vcf.gz:
	bgzip -c ${VCFs}/BCX_1014_6.hg19_multianno.vcf > BCX_1014_6.vcf.gz 
	bgzip -c ${VCFs}/BCX_1015_7.hg19_multianno.vcf > BCX_1015_7.vcf.gz 
	bgzip -c ${VCFs}/BCX_1016_8.hg19_multianno.vcf > BCX_1016_8.vcf.gz
	bgzip -c ${VCFs}/BCX_1017_9.hg19_multianno.vcf > BCX_1017_9.vcf.gz	
	bgzip -c ${VCFs}/BCX_1018_0.hg19_multianno.vcf > BCX_1018_0.vcf.gz
	bgzip -c ${VCFs}/BCX_1019_1.hg19_multianno.vcf > BCX_1019_1.vcf.gz
	bgzip -c ${VCFs}/BCX_1020_3.hg19_multianno.vcf > BCX_1020_3.vcf.gz 
	bgzip -c ${VCFs}/BCX_1021_4.hg19_multianno.vcf > BCX_1021_4.vcf.gz 
	bgzip -c ${VCFs}/BCX_1022_5.hg19_multianno.vcf > BCX_1022_5.vcf.gz 
	bgzip -c ${VCFs}/BCX_1023_6.hg19_multianno.vcf > BCX_1023_6.vcf.gz 
	bgzip -c ${VCFs}/BCX_1024_7.hg19_multianno.vcf > BCX_1024_7.vcf.gz 
	bgzip -c ${VCFs}/BCX_1025_8.hg19_multianno.vcf > BCX_1025_8.vcf.gz 
	bgzip -c ${VCFs}/BCX_1026_9.hg19_multianno.vcf > BCX_1026_9.vcf.gz 
	bgzip -c ${VCFs}/BCX_1027_0.hg19_multianno.vcf > BCX_1027_0.vcf.gz
	bgzip -c ${VCFs}/BCX_1106_8.hg19_multianno.vcf > BCX_1106_8.vcf.gz
	bgzip -c ${VCFs}/BCX_1107_9.hg19_multianno.vcf > BCX_1107_9.vcf.gz 
	bgzip -c ${VCFs}/BCX_1108_0.hg19_multianno.vcf > BCX_1108_0.vcf.gz
	bgzip -c ${VCFs}/BCX_1109_1.hg19_multianno.vcf > BCX_1109_1.vcf.gz 
	bgzip -c ${VCFs}/BCX_1110_3.hg19_multianno.vcf > BCX_1110_3.vcf.gz 
	bgzip -c ${VCFs}/Ot1652.hg19_multianno.vcf > Ot1652.vcf.gz
	bgzip -c ${VCFs}/Ot1653.hg19_multianno.vcf > Ot1653.vcf.gz
	bgzip -c ${VCFs}/Ot1654.hg19_multianno.vcf > Ot1654.vcf.gz 
	bgzip -c ${VCFs}/Ot1768.hg19_multianno.vcf > Ot1768.vcf.gz 
	bgzip -c ${VCFs}/Ot3114.hg19_multianno.vcf > Ot3114.vcf.gz 
	bgzip -c ${VCFs}/Ot3115.hg19_multianno.vcf > Ot3115.vcf.gz 
	bgzip -c ${VCFs}/Ot3116.hg19_multianno.vcf > Ot3116.vcf.gz 
	bgzip -c ${VCFs}/Ot3117.hg19_multianno.vcf > Ot3117.vcf.gz
	bgzip -c ${VCFs}/Ot3118.hg19_multianno.vcf > Ot3118.vcf.gz 
	bgzip -c ${VCFs}/Ot5727.hg19_multianno.vcf > Ot5727.vcf.gz 
	bgzip -c ${VCFs}/Ot5728.hg19_multianno.vcf > Ot5728.vcf.gz 
	bgzip -c ${VCFs}/Ot5729.hg19_multianno.vcf > Ot5729.vcf.gz
	bgzip -c ${VCFs}/Ot5730.hg19_multianno.vcf > Ot5730.vcf.gz 
	bgzip -c ${VCFs}/Ot5731.hg19_multianno.vcf > Ot5731.vcf.gz
	bgzip -c ${VCFs}/Ot5732.hg19_multianno.vcf > Ot5732.vcf.gz 
	bgzip -c ${VCFs}/Ot5733.hg19_multianno.vcf > Ot5733.vcf.gz
	bgzip -c ${VCFs}/Ot5734.hg19_multianno.vcf > Ot5734.vcf.gz
	bgzip -c ${VCFs}/Ot5735.hg19_multianno.vcf > Ot5735.vcf.gz 
	bgzip -c ${VCFs}/Ot6451.hg19_multianno.vcf > Ot6451.vcf.gz 
	bgzip -c ${VCFs}/Ot6452.hg19_multianno.vcf > Ot6452.vcf.gz 
	bgzip -c ${VCFs}/Ot6453.hg19_multianno.vcf > Ot6453.vcf.gz
	bgzip -c ${VCFs}/S0959.hg19_multianno.vcf > S0959.vcf.gz
	bgzip -c ${VCFs}/S0960.hg19_multianno.vcf > S0960.vcf.gz
	bgzip -c ${VCFs}/S0961.hg19_multianno.vcf > S0961.vcf.gz 
	bgzip -c ${VCFs}/S0962.hg19_multianno.vcf > S0962.vcf.gz
	bgzip -c ${VCFs}/S0963.hg19_multianno.vcf > S0963.vcf.gz 
	bgzip -c ${VCFs}/S0964.hg19_multianno.vcf > S0964.vcf.gz
	bgzip -c ${VCFs}/S0965.hg19_multianno.vcf > S0965.vcf.gz
	bgzip -c ${VCFs}/S0966.hg19_multianno.vcf > S0966.vcf.gz
	bgzip -c ${VCFs}/S0967.hg19_multianno.vcf > S0967.vcf.gz 
	bgzip -c ${VCFs}/S0968.hg19_multianno.vcf > S0968.vcf.gz
	bgzip -c ${VCFs}/S0969.hg19_multianno.vcf > S0969.vcf.gz 
	bgzip -c ${VCFs}/BCX_1103_5.hg19_multianno.vcf > BCX_1103_5.vcf.gz  
	bgzip -c ${VCFs}/BCX_1104_6.hg19_multianno.vcf > BCX_1104_6.vcf.gz     
	bgzip -c ${VCFs}/BCX_1091_1.hg19_multianno.vcf > BCX_1091_1.vcf.gz 
	bgzip -c ${VCFs}/BCX_1092_2.hg19_multianno.vcf > BCX_1092_2.vcf.gz   
	bgzip -c ${VCFs}/BCX_1093_3.hg19_multianno.vcf > BCX_1093_3.vcf.gz  	
	bgzip -c ${VCFs}/BCX_1001_2.hg19_multianno.vcf > BCX_1001_2.vcf.gz 
	bgzip -c ${VCFs}/BCX_1002_3.hg19_multianno.vcf > BCX_1002_3.vcf.gz   
	bgzip -c ${VCFs}/BCX_1088_7.hg19_multianno.vcf > BCX_1088_7.vcf.gz 
	bgzip -c ${VCFs}/BCX_1003_4.hg19_multianno.vcf > BCX_1003_4.vcf.gz  
	bgzip -c ${VCFs}/BCX_1004_5.hg19_multianno.vcf > BCX_1004_5.vcf.gz 
	bgzip -c ${VCFs}/BCX_1096_6.hg19_multianno.vcf > BCX_1096_6.vcf.gz  
	bgzip -c ${VCFs}/BCX_1005_6.hg19_multianno.vcf > BCX_1005_6.vcf.gz   
	bgzip -c ${VCFs}/BCX_1006_7.hg19_multianno.vcf > BCX_1006_7.vcf.gz  
	bgzip -c ${VCFs}/BCX_1098_8.hg19_multianno.vcf > BCX_1098_8.vcf.gz     
	bgzip -c ${VCFs}/BCX_1099_9.hg19_multianno.vcf > BCX_1099_9.vcf.gz 
	bgzip -c ${VCFs}/BCX_1100_2.hg19_multianno.vcf > BCX_1100_2.vcf.gz  
	bgzip -c ${VCFs}/BCX_1007_8.hg19_multianno.vcf > BCX_1007_8.vcf.gz 
	bgzip -c ${VCFs}/BCX_1008_9.hg19_multianno.vcf > BCX_1008_9.vcf.gz
	bgzip -c ${VCFs}/BCX_1009_0.hg19_multianno.vcf > BCX_1009_0.vcf.gz 
	bgzip -c ${VCFs}/BCX_1010_2.hg19_multianno.vcf > BCX_1010_2.vcf.gz  
	bgzip -c ${VCFs}/BCX_1101_3.hg19_multianno.vcf > BCX_1101_3.vcf.gz  
	bgzip -c ${VCFs}/BCX_1011_3.hg19_multianno.vcf > BCX_1011_3.vcf.gz  
	bgzip -c ${VCFs}/BCX_1102_4.hg19_multianno.vcf > BCX_1102_4.vcf.gz 
	bgzip -c ${VCFs}/BCX_1012_4.hg19_multianno.vcf > BCX_1012_4.vcf.gz
	bgzip -c ${VCFs}/BCX_1091_1.hg19_multianno.vcf > BCX_1091_1.vcf.gz 
S0969.vcf.gz.tbi: 
	tabix -p vcf BCX_1014_6.vcf.gz 
	tabix -p vcf BCX_1015_7.vcf.gz
	tabix -p vcf BCX_1016_8.vcf.gz
	#tabix -p vcf BCX_1017_9.vcf.gz
xx:	
	tabix -p vcf BCX_1018_0.vcf.gz
	tabix -p vcf BCX_1019_1.vcf.gz
	tabix -p vcf BCX_1020_3.vcf.gz
	tabix -p vcf BCX_1021_4.vcf.gz
	tabix -p vcf BCX_1022_5.vcf.gz
	tabix -p vcf BCX_1023_6.vcf.gz
	tabix -p vcf BCX_1024_7.vcf.gz
	tabix -p vcf BCX_1025_8.vcf.gz
	tabix -p vcf BCX_1026_9.vcf.gz
	tabix -p vcf BCX_1027_0.vcf.gz
	tabix -p vcf BCX_1106_8.vcf.gz
	tabix -p vcf BCX_1107_9.vcf.gz
	tabix -p vcf BCX_1108_0.vcf.gz
	tabix -p vcf BCX_1109_1.vcf.gz
	tabix -p vcf BCX_1110_3.vcf.gz
	tabix -p vcf Ot1652.vcf.gz
	tabix -p vcf Ot1653.vcf.gz
	tabix -p vcf Ot1654.vcf.gz
	tabix -p vcf Ot1768.vcf.gz
	tabix -p vcf Ot3114.vcf.gz
	tabix -p vcf Ot3115.vcf.gz
	tabix -p vcf Ot3116.vcf.gz
	tabix -p vcf Ot3117.vcf.gz
	tabix -p vcf Ot3118.vcf.gz
	tabix -p vcf Ot5727.vcf.gz
	tabix -p vcf Ot5728.vcf.gz
	tabix -p vcf Ot5729.vcf.gz
	tabix -p vcf Ot5730.vcf.gz
	tabix -p vcf Ot5731.vcf.gz
	tabix -p vcf Ot5732.vcf.gz
	tabix -p vcf Ot5733.vcf.gz
	tabix -p vcf Ot5734.vcf.gz
	tabix -p vcf Ot5735.vcf.gz
	tabix -p vcf Ot6451.vcf.gz
	tabix -p vcf Ot6452.vcf.gz
	tabix -p vcf Ot6453.vcf.gz
	tabix -p vcf S0959.vcf.gz
	tabix -p vcf S0960.vcf.gz
	tabix -p vcf S0961.vcf.gz
	tabix -p vcf S0962.vcf.gz
	tabix -p vcf S0963.vcf.gz
	tabix -p vcf S0964.vcf.gz
	tabix -p vcf S0965.vcf.gz
	tabix -p vcf S0966.vcf.gz
	tabix -p vcf S0967.vcf.gz
	tabix -p vcf S0968.vcf.gz
	tabix -p vcf S0969.vcf.gz
	tabix -p vcf BCX_1103_5.vcf.gz 
	tabix -p vcf BCX_1104_6.vcf.gz
	tabix -p vcf BCX_1091_1.vcf.gz 
	tabix -p vcf BCX_1092_2.vcf.gz 
	tabix -p vcf BCX_1093_3.vcf.gz 
	tabix -p vcf BCX_1001_2.vcf.gz 
	tabix -p vcf BCX_1002_3.vcf.gz 
	tabix -p vcf BCX_1088_7.vcf.gz 
	tabix -p vcf BCX_1003_4.vcf.gz 
	tabix -p vcf BCX_1004_5.vcf.gz
	tabix -p vcf BCX_1096_6.vcf.gz 
	tabix -p vcf BCX_1005_6.vcf.gz 
	tabix -p vcf BCX_1006_7.vcf.gz 
	tabix -p vcf BCX_1098_8.vcf.gz       
	tabix -p vcf BCX_1099_9.vcf.gz
	tabix -p vcf BCX_1100_2.vcf.gz
	tabix -p vcf BCX_1007_8.vcf.gz 
	tabix -p vcf BCX_1008_9.vcf.gz 
	tabix -p vcf BCX_1009_0.vcf.gz  
	tabix -p vcf BCX_1010_2.vcf.gz 
	tabix -p vcf BCX_1101_3.vcf.gz 
	tabix -p vcf BCX_1011_3.vcf.gz 
	tabix -p vcf BCX_1102_4.vcf.gz 
	tabix -p vcf BCX_1012_4.vcf.gz
	tabix -p vcf BCX_1091_1.vcf.gz 



wes47.vcf: S0969.vcf.gz.tbi
	vcf-merge BCX_1014_6.vcf.gz BCX_1015_7.vcf.gz BCX_1016_8.vcf.gz BCX_1017_9.vcf.gz BCX_1018_0.vcf.gz BCX_1019_1.vcf.gz BCX_1020_3.vcf.gz BCX_1021_4.vcf.gz \
	BCX_1022_5.vcf.gz BCX_1023_6.vcf.gz BCX_1024_7.vcf.gz BCX_1025_8.vcf.gz BCX_1026_9.vcf.gz BCX_1027_0.vcf.gz BCX_1106_8.vcf.gz BCX_1107_9.vcf.gz \
	BCX_1108_0.vcf.gz BCX_1109_1.vcf.gz BCX_1110_3.vcf.gz Ot1652.vcf.gz Ot1653.vcf.gz Ot1654.vcf.gz Ot3114.vcf.gz Ot3115.vcf.gz Ot3116.vcf.gz \
	Ot3117.vcf.gz Ot3118.vcf.gz Ot5727.vcf.gz Ot5728.vcf.gz Ot5729.vcf.gz Ot5730.vcf.gz Ot5731.vcf.gz Ot5732.vcf.gz Ot5733.vcf.gz Ot5734.vcf.gz \
	Ot5735.vcf.gz S0959.vcf.gz S0960.vcf.gz S0961.vcf.gz S0962.vcf.gz S0963.vcf.gz S0964.vcf.gz S0965.vcf.gz S0966.vcf.gz S0967.vcf.gz S0968.vcf.gz \
	S0969.vcf.gz > wes47.vcf

#BCX_1105_7.vcf.gz BCX_1094_4.vcf.gz BCX_1095_5.vcf.gz  BCX_1097_7.vcf.gz DO NOT EXIST 
prl.vcf: S0969.vcf.gz.tbi
	vcf-merge BCX_1103_5.vcf.gz BCX_1104_6.vcf.gz BCX_1014_6.vcf.gz BCX_1015_7.vcf.gz BCX_1016_8.vcf.gz \
	BCX_1017_9.vcf.gz BCX_1018_0.vcf.gz BCX_1019_1.vcf.gz BCX_1020_3.vcf.gz BCX_1021_4.vcf.gz BCX_1022_5.vcf.gz BCX_1023_6.vcf.gz \
	BCX_1024_7.vcf.gz BCX_1025_8.vcf.gz BCX_1026_9.vcf.gz BCX_1027_0.vcf.gz Ot5733.vcf.gz Ot5734.vcf.gz BCX_1106_8.vcf.gz Ot5735.vcf.gz \
	BCX_1107_9.vcf.gz BCX_1108_0.vcf.gz BCX_1109_1.vcf.gz BCX_1110_3.vcf.gz BCX_1091_1.vcf.gz BCX_1092_2.vcf.gz BCX_1093_3.vcf.gz \
	BCX_1001_2.vcf.gz BCX_1002_3.vcf.gz BCX_1088_7.vcf.gz BCX_1003_4.vcf.gz BCX_1004_5.vcf.gz \
	BCX_1096_6.vcf.gz BCX_1005_6.vcf.gz BCX_1006_7.vcf.gz BCX_1098_8.vcf.gz BCX_1099_9.vcf.gz BCX_1100_2.vcf.gz \
	BCX_1007_8.vcf.gz BCX_1008_9.vcf.gz BCX_1009_0.vcf.gz BCX_1010_2.vcf.gz BCX_1101_3.vcf.gz BCX_1011_3.vcf.gz BCX_1102_4.vcf.gz BCX_1012_4.vcf.gz \
	BCX_1013_5.vcf.gz BCX_1089_8.vcf.gz BCX_1090_0.vcf.gz > prl.vcf   


cushing.vcf: S0969.vcf.gz.tbi
	vcf-merge S0962.vcf.gz S0963.vcf.gz S0964.vcf.gz S0965.vcf.gz S0966.vcf.gz S0967.vcf.gz S0968.vcf.gz S0969.vcf.gz > cushing.vcf 
        

acromegaly.vcf: S0969.vcf.gz.tbi
	vcf-merge Ot5730.vcf.gz Ot5731.vcf.gz Ot5732.vcf.gz S0959.vcf.gz S0960.vcf.gz S0961.vcf.gz > acromegaly.vcf  

trimmed-wes78.vcf.gz:   
	head -10133717 wes78.vcf > trimmed-wes78.vcf
	(grep ^"#" trimmed-wes78.vcf; grep -v ^"#" trimmed-wes78.vcf | sed 's:^chr::ig' | sort -k1,1n -k2,2n) | bgzip -c > trimmed-wes78.vcf.gz
	tabix -p vcf trimmed-wes78.vcf.gz




rvp01.CMC.assoc: trimmed-wes78.vcf.gz  
	${RVTESTS}/rvtest --inVcf trimmed-wes78.vcf.gz --pheno wes78.ped \
	--freqUpper 0.01 --out rvp01  --geneFile refFlat_hg19.txt.gz \
	--burden cmc



		
rvp01.Skat.assoc: trimmed-wes78.vcf.gz
	${RVTESTS}/rvtest --inVcf trimmed-wes78.vcf.gz --pheno wes78.ped \
	--freqUpper 0.01 --out rvp01 --geneFile refFlat_hg19.txt.gz \
	--kernel skat


rvp01.VariableThresholdPrice.assoc: trimmed-wes78.vcf.gz   
	${RVTESTS}/rvtest --inVcf trimmed-wes78.vcf.gz --pheno wes78.ped \
        --freqUpper 0.01 --out rvp01 --geneFile refFlat_hg19.txt.gz \
        --vt price


rvp01.SkatO.assoc: trimmed-wes78.vcf.gz  
	${RVTESTS}/rvtest --inVcf trimmed-wes78.vcf.gz --pheno wes78.ped \
	--freqUpper 0.01 --out rvp01 --geneFile refFlat_hg19.txt.gz \
	--kernel skato


rvp01.SingleWald.assoc: trimmed-wes78.vcf.gz  
	${RVTESTS}/rvtest --inVcf trimmed-wes78.vcf.gz --pheno wes78.ped \
        --freqUpper 0.01 --out rvp01 --geneFile refFlat_hg19.txt.gz \
        --single wald



rvp01-genes.CMC.assoc: trimmed-wes78.vcf.gz
	 ${RVTESTS}/rvtest --inVcf trimmed-wes78.vcf.gz --pheno wes78.ped \
	--freqUpper 0.01 --out rvp01-genes --gene ${GENES} --geneFile refFlat_hg19.txt.gz \
	--burden cmc


rvp01-genes.CMAT.assoc: trimmed-wes78.vcf.gz
	${RVTESTS}/rvtest --inVcf trimmed-wes78.vcf.gz --pheno wes78.ped \
	--freqUpper 0.01 --out rvp01-genes --gene ${GENES} --geneFile refFlat_hg19.txt.gz \
	--burden cmat


rvp01-genes.FamCMC.assoc: trimmed-wes78.vcf.gz
	${RVTESTS}/rvtest --inVcf trimmed-wes78.vcf.gz --pheno wes78.ped \
	--freqUpper 0.01 --out rvp01-genes --gene ${GENES} --geneFile refFlat_hg19.txt.gz \
	--kinship wes78.kinship  --burden famcmc 


rvp01-genes.CMCWald.assoc: trimmed-wes78.vcf.gz
	${RVTESTS}/rvtest --inVcf trimmed-wes78.vcf.gz --pheno wes78.ped \
	--freqUpper 0.01 --out rvp01-genes --gene ${GENES} --geneFile refFlat_hg19.txt.gz \
	--burden cmcWald

rvp01-genes.RareCover.assoc: trimmed-wes78.vcf.gz
	${RVTESTS}/rvtest --inVcf trimmed-wes78.vcf.gz --pheno wes78.ped \
	--freqUpper 0.01 --out rvp01-genes --gene ${GENES} --geneFile refFlat_hg19.txt.gz \
	--burden rarecover



rvp01-genes.Zeggini.assoc: trimmed-wes78.vcf.gz
	${RVTESTS}/rvtest --inVcf trimmed-wes78.vcf.gz --pheno wes78.ped \
	--freqUpper 0.01 --out rvp01-genes --gene ${GENES} --geneFile refFlat_hg19.txt.gz \
	--burden zeggini



rvp01-genes.MadsonBrowning.assoc: trimmed-wes78.vcf.gz
	${RVTESTS}/rvtest --inVcf trimmed-wes78.vcf.gz --pheno wes78.ped \
	--freqUpper 0.01 --out rvp01-genes --gene ${GENES} --geneFile refFlat_hg19.txt.gz \
	--burden mb


rvp01-genes.Skat.assoc: trimmed-wes78.vcf.gz
	${RVTESTS}/rvtest --inVcf trimmed-wes78.vcf.gz --pheno wes78.ped \
	--freqUpper 0.01 --out rvp01-genes --gene ${GENES} --geneFile refFlat_hg19.txt.gz \
	--kernel skat


rvp01-genes.kbac.assoc: trimmed-wes78.vcf.gz
	${RVTESTS}/rvtest --inVcf trimmed-wes78.vcf.gz --pheno wes78.ped \
	--freqUpper 0.01 --out rvp01-genes --gene ${GENES} --geneFile refFlat_hg19.txt.gz \
	--kernel kbac


rvp01-genes.VariableThresholdPrice.assoc: trimmed-wes78.vcf.gz
	${RVTESTS}/rvtest --inVcf trimmed-wes78.vcf.gz --pheno wes78.ped \
	--freqUpper 0.01 --out rvp01-genes --gene ${GENES} --geneFile refFlat_hg19.txt.gz \
	--vt price


rvp01-genes.SkatO.assoc: trimmed-wes78.vcf.gz
	${RVTESTS}/rvtest --inVcf trimmed-wes78.vcf.gz --pheno wes78.ped \
	--freqUpper 0.01 --out rvp01-genes --gene ${GENES} --geneFile refFlat_hg19.txt.gz \
	--kernel skato


rvp01-genes.SingleWald.assoc: trimmed-wes78.vcf.gz
	${RVTESTS}/rvtest --inVcf trimmed-wes78.vcf.gz --pheno wes78.ped \
	--freqUpper 0.01 --out rvp01-genes --gene ${GENES} --geneFile refFlat_hg19.txt.gz \
	--single wald



rvp01-genes.bolt.assoc: trimmed-wes78.vcf.gz
	${RVTESTS}/rvtest --inVcf trimmed-wes78.vcf.gz --pheno wes78.ped \
	--freqUpper 0.01 --out rvp01-genes --gene ${GENES} --geneFile refFlat_hg19.txt.gz \
	--meta bolt


#============================================================================WES47================================================================
trimmed-wes47.vcf.gz:   
	(grep ^"#" trimmed-wes47.vcf; grep -v ^"#" trimmed-wes47.vcf | sed 's:^chr::ig' | sort -k1,1n -k2,2n) | bgzip -c > trimmed-wes47.vcf.gz
	tabix -p vcf trimmed-wes47.vcf.gz

rv47.CMC.assoc: trimmed-wes47.vcf.gz
	${RVTESTS}/rvtest --inVcf trimmed-wes47.vcf.gz --pheno wes47.ped \
	--freqUpper 0.1 --out rv47  --geneFile refFlat_hg19.txt.gz \
	--burden cmc

rv47.Skat.assoc: trimmed-wes47.vcf.gz
	${RVTESTS}/rvtest --inVcf trimmed-wes47.vcf.gz --pheno wes47.ped \
	--freqUpper 0.1 --out rv47 --geneFile refFlat_hg19.txt.gz \
	--kernel skat

rv47.VariableThresholdPrice.assoc: trimmed-wes47.vcf.gz
	${RVTESTS}/rvtest --inVcf trimmed-wes47.vcf.gz --pheno wes47.ped \
	--freqUpper 0.1 --out rv47 --geneFile refFlat_hg19.txt.gz \
	--vt price

rv47.SkatO.assoc: trimmed-wes47.vcf.gz 
	${RVTESTS}/rvtest --inVcf trimmed-wes47.vcf.gz --pheno wes47.ped \
	--freqUpper 0.1 --out rv47 --geneFile refFlat_hg19.txt.gz \
	--kernel skato


rv47.SingleWald.assoc: trimmed-wes47.vcf.gz
	${RVTESTS}/rvtest --inVcf trimmed-wes47.vcf.gz --pheno wes47.ped \
	--freqUpper  0.1 --out rv47 --geneFile refFlat_hg19.txt.gz \
	--single wald

#===============================================================================Prolactinoma=================================================================
trimmed-prl.vcf.gz: 	
	(grep ^"#" trimmed-prl.vcf; grep -v ^"#" trimmed-prl.vcf | sed 's:^chr::ig' | sort -k1,1n -k2,2n) | bgzip -c > trimmed-prl.vcf.gz 
	tabix -p vcf trimmed-prl.vcf.gz 


rvprl.CMC.assoc: 	trimmed-prl.vcf.gz
	${RVTESTS}/rvtest --inVcf trimmed-prl.vcf.gz --pheno prl.ped \
	--freqUpper 0.1 --out rvprl --geneFile refFlat_hg19.txt.gz \
	--burden cmc

rvprl.Skat.assoc: trimmed-prl.vcf.gz
	${RVTESTS}/rvtest --inVcf trimmed-prl.vcf.gz --pheno prl.ped \
	--freqUpper 0.1 --out rvprl --geneFile refFlat_hg19.txt.gz \
	--kernel skat

rvprl.VariableThresholdPrice.assoc: trimmed-prl.vcf.gz
	${RVTESTS}/rvtest --inVcf trimmed-prl.vcf.gz --pheno prl.ped \
	--freqUpper 0.1 --out rvprl --geneFile refFlat_hg19.txt.gz \
	--vt price


rvprl.SkatO.assoc: trimmed-prl.vcf.gz
	${RVTESTS}/rvtest --inVcf trimmed-prl.vcf.gz --pheno prl.ped \
	--freqUpper 0.1 --out rvprl --geneFile refFlat_hg19.txt.gz \
	--kernel skato


rvprl.SingleWald.assoc: trimmed-prl.vcf.gz
	${RVTESTS}/rvtest --inVcf trimmed-prl.vcf.gz --pheno prl.ped \
	--freqUpper 0.1 --out rvprl --geneFile refFlat_hg19.txt.gz \
	--single wald




#========================================================================Cushing========================================================================================
trimmed-cushing.vcf: cushing.vcf 
	head -4247853 cushing.vcf > trimmed-cushing.vcf

trimmed-cushing.vcf.gz:trimmed-cushing.vcf 
	(grep ^"#" trimmed-cushing.vcf; grep -v ^"#" trimmed-cushing.vcf | sed 's:^chr::ig' | sort -k1,1n -k2,2n) | bgzip -c > trimmed-cushing.vcf.gz 
	tabix -p vcf trimmed-cushing.vcf.gz 

rvcushing.CMC.assoc:        trimmed-cushing.vcf.gz
	${RVTESTS}/rvtest --inVcf trimmed-cushing.vcf.gz --pheno cushing.ped \
	--freqUpper 0.1 --out rvcushing --geneFile refFlat_hg19.txt.gz \
	--burden cmc

rvcushing.Skat.assoc: trimmed-cushing.vcf.gz
	${RVTESTS}/rvtest --inVcf trimmed-cushing.vcf.gz --pheno cushing.ped \
	--freqUpper 0.1 --out rvcushing --geneFile refFlat_hg19.txt.gz \
	--kernel skat

rvcushing.VariableThresholdPrice.assoc: trimmed-cushing.vcf.gz
	${RVTESTS}/rvtest --inVcf trimmed-cushing.vcf.gz --pheno cushing.ped \
	--freqUpper 0.1 --out rvcushing --geneFile refFlat_hg19.txt.gz \
	--vt price

rvcushing.SkatO.assoc: trimmed-cushing.vcf.gz
	${RVTESTS}/rvtest --inVcf trimmed-cushing.vcf.gz --pheno cushing.ped \
	--freqUpper 0.1 --out rvcushing --geneFile refFlat_hg19.txt.gz \
	--kernel skato

rvcushing.SingleWald.assoc: trimmed-cushing.vcf.gz
	${RVTESTS}/rvtest --inVcf trimmed-cushing.vcf.gz --pheno cushing.ped \
	--freqUpper 0.1 --out rvcushing --geneFile refFlat_hg19.txt.gz \
	--single wald
#======================================================================Acromegaly=========================================================================================
trimmed-acromegaly.vcf: acromegaly.vcf
	head -2886957 acromegaly.vcf > trimmed-acromegaly.vcf 

trimmed-acromegaly.vcf.gz: trimmed-acromegaly.vcf
	(grep ^"#" trimmed-acromegaly.vcf; grep -v ^"#" trimmed-acromegaly.vcf | sed 's:^chr::ig' | sort -k1,1n -k2,2n) | bgzip -c > trimmed-acromegaly.vcf.gz 
	tabix -p vcf trimmed-acromegaly.vcf.gz 

rvacromegaly.CMC.assoc:        trimmed-acromegaly.vcf.gz
	${RVTESTS}/rvtest --inVcf trimmed-acromegaly.vcf.gz --pheno acromegaly.ped \
	--freqUpper 0.1 --out rvacromegaly --geneFile refFlat_hg19.txt.gz \
	--burden cmc

rvacromegaly.Skat.assoc: trimmed-acromegaly.vcf.gz
	${RVTESTS}/rvtest --inVcf trimmed-acromegaly.vcf.gz --pheno acromegaly.ped \
	--freqUpper 0.1 --out rvacromegaly --geneFile refFlat_hg19.txt.gz \
	--kernel skat

rvacromegaly.VariableThresholdPrice.assoc: trimmed-acromegaly.vcf.gz
	${RVTESTS}/rvtest --inVcf trimmed-acromegaly.vcf.gz --pheno acromegaly.ped \
	--freqUpper 0.1 --out rvacromegaly --geneFile refFlat_hg19.txt.gz \
	--vt price

rvacromegaly.SkatO.assoc: trimmed-acromegaly.vcf.gz
	${RVTESTS}/rvtest --inVcf trimmed-acromegaly.vcf.gz --pheno acromegaly.ped \
	--freqUpper 0.1 --out rvacromegaly --geneFile refFlat_hg19.txt.gz \
	--kernel skato

rvacromegaly.SingleWald.assoc: trimmed-acromegaly.vcf.gz
	${RVTESTS}/rvtest --inVcf trimmed-acromegaly.vcf.gz --pheno acromegaly.ped \
	--freqUpper 0.1 --out rvacromegaly --geneFile refFlat_hg19.txt.gz \
#=========================================================================Filter=========================================================================================
	
prl.skato: 
	awk '$7 <= 0.005 {print $0}' rvprl.CMC.assoc > prl.cmc 
	awk '$13 <= 0.005 {print $0}' rvprl.Skat.assoc > prl.skat
	awk '$13 <= 0.005 {print $0}' rvprl.VariableThresholdPrice.assoc > prl.price
	awk '$8 <= 0.005 {print $0}' rvprl.SkatO.assoc > prl.skato 


47.skato: 
	awk '$7 <= 0.005 {print $0}' rv47.CMC.assoc > 47.cmc 
	awk '$13 <= 0.005 {print $0}' rv47.Skat.assoc > 47.skat
	awk '$13 <= 0.005 {print $0}' rv47.VariableThresholdPrice.assoc > 47.price
	awk '$8 <= 0.005 {print $0}' rv47.SkatO.assoc > 47.skato 


	
