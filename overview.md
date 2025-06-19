# End-to-End Automation Pipeline

CUBE.AI Platform enables radiologists to create and refine segmentation models independently, without expert involvement. Data is fetched from PACS for either training a new model or improving an existing one. Using an assisted segmentation tool powered by foundational models from the model bank, radiologists can annotate studies with simple prompts like positive points, negative points, or bounding boxes.

Training is fully automated via a self-configuring framework, followed by validation, where accuracy metrics and results are presented to the radiologist. The trained model is then automatically deployed to the model bank for integration into the assisted segmentation tool. This same process can be used to enhance existing models.