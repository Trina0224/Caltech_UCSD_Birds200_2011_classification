# Caltech_UCSD_Birds200_2011_classification
200 Birds classification


keep working ...

Everything is based on the script Google provide and Caltech-UCSD
http://storage.googleapis.com/cloud-iot-edge-pretrained-models/docker/classify_scripts.tgz

https://github.com/tensorflow/models.git
and
http://www.vision.caltech.edu/visipedia/CUB-200-2011.html


Please replace related files in docker /research/slim and /research/slim/dataset
I cp some files and end at _birds.sh or _birds.py for easy reading and managements. But, dataset_factory.py in slim/dataset, I keep the original name because other python script need it.





====================================================

Citation

If you use CUB-200-2011 in your work, please cite the technical report:

Wah C., Branson S., Welinder P., Perona P., Belongie S. “The Caltech-UCSD Birds-200-2011 Dataset.” Computation & Neural Systems Technical Report, CNS-TR-2011-001. download pdf

BibTeX

@techreport{WahCUB_200_2011,
	Title = {{The Caltech-UCSD Birds-200-2011 Dataset}},
	Author = {Wah, C. and Branson, S. and Welinder, P. and Perona, P. and Belongie, S.},
	Year = {2011}
	Institution = {California Institute of Technology},
	Number = {CNS-TR-2011-001}
}
