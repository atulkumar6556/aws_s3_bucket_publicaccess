# AWS S3 BUCKET PUBLIC ACCESS
## aws_s3_bucket_publicaccess
give your aws s3 bucket public access





-----------------------------------------------------------------------------------------------
## STEP 1:
### OPEN BUCKET THAT YOU WANT MAKE PUBLIC

 <p align="center">
<!--   <img src="your_relative_path_here" width="350" title="hover text"> -->
  <img src="https://drive.google.com/uc?export=download&id=1M1_vTPYSJOqJmYVxSRIrr2Y4LQBeLJ6u" width="950" alt="STEP1">
</p>

-------------------------------------------------------------------------------------------------
## STEP 2:
### CLICK ON PERMISSIONS

<p align="center">
<!--   <img src="your_relative_path_here" width="350" title="hover text"> -->
  <img src="https://drive.google.com/uc?export=download&id=1MrYaopQ96XEA4ULiz7-yfoz5A3s4Gv7L" width="950" alt="STEP2">
</p>

 ------------------------------------------------------------------------------------------------
 ## STEP 3:
### MAKE SURE YOUR BLOCK ALL PUBLIC SERVICE IS OFF        
<p align="center">
<!--   <img src="your_relative_path_here" width="350" title="hover text"> -->
  <img src="https://drive.google.com/uc?export=download&id=1Mzv1IXfTYS9s006e_gMAknl0h7nQMnF1" width="950" alt="STEP3">
</p>
 
---------------------------------------------------------------------------------------------------
## STEP 4:
### CLICK ON BUCKET POLICY TO EDIT        
<p align="center">
<!--   <img src="your_relative_path_here" width="350" title="hover text"> -->
  <img src="https://drive.google.com/uc?export=download&id=14PVhDo-VAXWh4GNKKX_QQyaQ6_i9FuY1" width="950" alt="STEP4">
</p>

----------------------------------------------------------------------------------------------------

## STEP 5:
### REPLACE CODE WITH GIVEN CODE BELOW    

<p align="center">
          <!--   <img src="your_relative_path_here" width="350" title="hover text"> -->
<img src="https://drive.google.com/uc?export=download&id=10bAN_PsGk39tj3S0bWC9bwBWqnQZCqYQ" width="950" alt="STEP5">
</p>
          
  -------------------------------------------------------------------------------------------------------
          
          
          {
              "Version": "2008-10-17",
              "Statement": [
                  {
                      "Sid": "AddPerm",
                      "Effect": "Allow",
                      "Principal": "*",
                      "Action": "s3:GetObject",
                      "Resource": "arn:aws:s3:::youbucketname/*"
                  }
              ]
          }


----------------------------------------------------------------------------------------------------

## STEP 6:
### SAVE IT ,NOW YOUR BUCKET PUBLICALLY ACCESSABLE     

<p align="center">
          <!--   <img src="your_relative_path_here" width="350" title="hover text"> -->
<img src="https://drive.google.com/uc?export=download&id=1ESFzrGAOeG33nX5o8sAt_B3gyZBVLeno" width="950" alt="STEP6">
</p>

----------------------------------------------------------------------------------------------------


          ### IOT DEVELOPER
          ATUL KUMAR
