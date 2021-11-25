Story: Sohail and his family had plans to visit Bangkok this summer vacation. Unfortunately, they had to cancel the trip due to COVID situation in his country.

However, Sohail decided to play a prank on his friends. Using his programming skills, he decided to create pictures of herself containing the background of the famous places in Bangkok City - The Grand Palace, Temple of Emerald Buddha etc. He would then send these pictures to his friends as if he is already on the planned trip.

In class 21, we created an invisible cloak by masking the ‘red’ color in the user video image with the user’s background.

In this project, we have to practice and apply what we have learned in the class. We will be modifying the background of the user with any other background.

Steps: 
 
1.) Open VS Code Editor and create a file called blackscreen.py

2.) Import the cv2 and numpy libraries.

3.) Start the video capture.

4.) Read the image which will be shown when the black object will get masked and save it in an “image” variable.

5.) Start reading the frames of the video.

6.) Resize the image and the video to 640, 480.

7.)Create an array of RGB of faint black color shade and dark shade of black and store in the l_black and u_black respectively.

8.) Create a mask using cv’s inRange() function and pass the frame , l_black and u_black as the parameters.

9.) Using np.where() function to return frame or image if the value of f is 0.

10.) Show the real video and masked video.

11.) Break the loop if the user presses “Esc” or “Q”.

12.) Release the video and close the video windows.

13.) Run and test the code.
