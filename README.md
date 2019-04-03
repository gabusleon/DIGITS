# DIGITS

This project has been cloned from git clone http://github.com/NVIDIA/DIGITS.git ~/digits and it has been updated to prevent Pickle error at the time to save or load a job.

It has been replaced all 'import caffe_pb2' with 'import caffe.proto.caffe_pb2 as caffe_pb2' as shown in issue 2024 of DIGITS github workspace (see, https://github.com/NVIDIA/DIGITS/issues/2024).
