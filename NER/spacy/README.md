# NER Spacy Documentation

## Version
* spaCy 3.0

## Training
1. From terminal, navigate to NLPRecipeRecommender/NER/spacy/training
2. Run training pipeline 
    * CPU Version
        * Run the following command given pre-set up data
            * python -m spacy train configs/config.cfg --output ./training_output --paths.train data/train/ --paths.dev data/test/
    * GPU Version
        * Run the following command given pre-set up data
            * python -m spacy train configs/gpu_config.cfg --output ./gpu_training_output --path.train data/train/ --paths.dev data/test/
