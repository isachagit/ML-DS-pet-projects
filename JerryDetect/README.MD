JerryDetect is a part of a project which helps to track my dog(Jerry) using smart camera situated at home.  
I used FasterRCNN_ResNet50_FPN, but the problem was in wrong recognition of Jerry as a teddy bear.  
So i added the new object named "Jerry", created custom dataset and trained my model.  

Directories:
- --pics_train/     --- pictures that were used to train model
- --vids_detected/           --- ready videos with red rectangle - area where Jerry is located
- --vids_test/               --- raw videos where Jerry must be detected
