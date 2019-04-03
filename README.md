# DIGITS

This project has been cloned from http://github.com/NVIDIA/DIGITS.git and it has been updated to prevent pickle error at the time to save or load a job.

To prevent this error, it has been replaced all 'import caffe_pb2' with 'import caffe.proto.caffe_pb2 as caffe_pb2' as shown in issue 2024 of DIGITS github workspace (see, https://github.com/NVIDIA/DIGITS/issues/2024).
