# 3DFaceRecontruction
Reconstruct 3D face from video. From DenseFace3D
An example result is shown in video "3d_reconstruction_result.mp4"

#Usage

mkdir build
cd build
cmake .. -Ddlib_DIR=path/to/dlib/ 
make

Copy the landmark.txt and conn.txt to build folder along with the 'shape_predictor_68_face_landmarks.dat'

To run,

./denseFace3D /path_to_video_file
