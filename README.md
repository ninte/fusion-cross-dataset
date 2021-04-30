# Fusion-Makers and Fusion-Models cross-datasets
This repository contains the correspondence between classes of CompCars, VMMR-db and Frontal-103 to build the Fusion-Makers and Fusion-Models cross dataset presented in "Are we ready for accurate fine-grained vehicle classification in the wild?"

| Dataset       | # Classes | # Images | # CompCars (%) | # VMMR-db (%)   | # Frontal-103 (%) |
|---------------|-----------|----------|----------------|-----------------|-------------------|
| Fusion-Makers | 27        | 265,833   | 28,960 (10.89%) | 198,644 (74.73%) | 38,229 (14.38%)    |
| Fusion-Models | 75        | 101,335   | 13,211 (13.04%) | 72,142 (71.19%)  | 15,982 (15.77%)    |


## Fusion-Makers
The Fusion-Makers set has 27 different manufacturers and a total of 265,833 images: 28,960 from CompCars, 198,644 from VMMR-db and 38,229 from Frontal-103.

The manufacturers present in this set are: Audi, BMW, Buick, Cadillac, Chevrolet, Chrysler, FIAT, Ford, Honda, Infiniti, Jaguar, Jeep, KIA, LAND-ROVER, Lexus, MAZDA, MINI, Mercedes, Mitsubishi, Nissan, Porsche, Saab, Smart, Subaru, Suzuki, Toyota and Volkswagen.

The file [FusionMakers.txt](https://github.com/ninte/fusion-cross-dataset/blob/main/FusionMakers.txt) contains the classes id correspondences between the Fusion-Makers set and the source datasets (CompCars, VMMR-db and Frontal-103). It also has a relation of the classes folder names of each of the source datasets.


## Fusion-Models
TheFusion-Models set has 75 different vehicle models and a total of 101,335 images, 13,211 from CompCars, 72,142 from VMMR-db and 15,982 from Frontal-103.

The models present in this set are: Audi A3, Audi A4, Audi A6, Audi A8, Audi Q7, Audi TT, BMW series 1, BMW series 3, BMW series 5, BMW series 6, BMW series 7, BMW X3, BMW X5, Buick Lacrosse, Buick Regal, Cadillac CTS, Cadillac SRX, Cadillac XTS, Chevrolet Aveo, Chevrolet Camaro, Chevrolet Cruze, Chevrolet Malibu, Chrysler 300, Fiat 500, Ford Mustang, Honda Accord, Honda Civic, Honda CR-V, Infiniti G, JEEP Compass, KIA Forte, KIA Sorento, KIA Soul, KIA Sportage, Land Rover Discovery, Land Rover Range Rover, Lexus CT, Lexus ES, Lexus GS, Lexus GX, Lexus IS, Lexus RX, Mazda 2, Mazda 3, Mazda 5, Mazda 6, Mazda CX7, Mercedes C, Mercedes E, Mercedes GL, Mercedes GLK, Mercedes S, Mercedes SLK, Mini Cooper, Mitsubishi Lancer, Mitsubishi Montero, Mitsubishi Outlander, Nissan GTR, Porsche 911, Porsche Cayenne, Porsche Panamera, Smart fortwo, Toyota Camry, Toyota LandCruiser, Toyota Prius, Toyota RAV4, Toyota Yaris, Volkswagen Beetle, Volkswagen CC, Volkswagen EOS, Volkswagen Golf, Volkswagen Jetta, Volkswagen Passat, Volkswagen Tiguan and Volkswagen Touareg.

The file [FusionModels.txt](https://github.com/ninte/fusion-cross-dataset/blob/main/FusionModels.txt) contains the classes id correspondences between the Fusion-Models set and the source datasets (CompCars, VMMR-db and Frontal-103).


## Cooming soon
Two .json files with the name of each image for the train and validation splits of both Fusion sets will be available soon.