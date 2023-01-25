# LOCO: Logistics Objects in Context

LOCO is the first scene understanding dataset for logistics covering the problem of detecting logistics-specific objects. Images are captured while walking through a logistics setting using low-cost cameras. We currently provide 37,988 images captured in 5 logistics environments, of which 5593 images are manually annotated, resulting in 152,421 annotations. Annotated classes include forklifts, pallet trucks, pallets, small load carriers and stillages.  

<div style="text-align:center"><img src="./assets/loco_sample_images.png" /></div>

For more details, we refer to our [paper](https://mediatum.ub.tum.de/doc/1578845/1578845.pdf). If you use LOCO for your research, please consider citeing our work ([Bibtex](https://mediatum.ub.tum.de/export/1578845/bibtex)).

## Dataset
### Data
The annotated dataset can be downloaded [here](https://go.mytum.de/239870). Furthermore, we also provide additional data (not annotated) [here](http://go.mytum.de/928009).
### Annotations 
Annotations are stored in [COCO format](https://cocodataset.org/#format-data) under `rgb/loco-all-v1.json`. For ease of use, we also provide seperate annotation files for each subset. 

We also provide annotations in [YOLO format](https://docs.ultralytics.com/hub/) inside `YOLO/labels.zip`. For quick experimentation, all the corresponding `images` can be dowloaded [here](https://drive.google.com/file/d/1yzN65mNnAY1_3I-Qw9WYWnslbnhs-d4h/view). 
  
## Credits & How to cite
This project would not have been possible without the amazing team including Dimitrij-Marian Holm, Benjamin Molter, Nikolai Ruof and Mubashir Hanif as well as all the hardworking annotators.

The dataset in this repository is maintained by [Christopher Mayershofer](mayershofer.com). 

If you use the dataset contained in this repository for your research, please cite the following publication:
>LOCO: Logistics Objects in Context    
>Mayershofer, C., Holm, D.-M., Molter, B., Fottner, J.     
>IEEE International Conference on Machine Learning and Applications (ICMLA) 2020

## License
The person who associated a work with this deed has dedicated the work to the public domain by waiving all of his or her rights to the work worldwide under copyright law, including all related and neighboring rights, to the extent allowed by law.

You can copy, modify, distribute and perform the work, even for commercial purposes, all without asking permission. See [LICENSE](./LICENSE) for details.

