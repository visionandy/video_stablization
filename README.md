# video_stablization
This is the modificated version, modify several parameters in the original codebase for direct use.
One typical example is
def test_func():
   from vidstab.VidStab import VidStab 
   stabilizer = VidStab()         
   stabilizer.stabilize(input_path='../t.mp4', output_path='stable_video.avi')  
Note: 
1. There are three options for the boundry processing.
2. You can also choose several different features for keypoint extractions.
