# PPE_Detection_YOLOv5
Degree Work - Detection of Personal Protective Equipment (PPE) Using Computer Vision Based YOLOv5 Algorithm
Link to download a Dataset (roboflow) - https://drive.google.com/drive/folders/1-4z3421NQNP1OOEMcBK9OWN0jp4dDel9?usp=sharing
You can download the DB from roboflow API the code in jupiter notebook attached ,We run on GoogleCollab Pro (not really need) , all process recorded with wandb.ai 
7 Object Recognition - Hardhat , Vest , Worker , Raspiration Mask , Googles , Ear Protection , Gloves 
YOLOv5x (with Auto Batch) give us best results 68% mAP for all objects , 90% mAP for Worker, Vest , Hardhat 
We advise to add a quality pictures to DB and use a small DB , 1K quality pics is enought to make great results 
Critical is to annotate all your train objects in all pictures !!!
Use Roboflow it's free & very easy to understand not like labelimg (for more pro works) until some time :) 

