## 1、target_include_directories
```
path/to/onnxruntime-static-lib/include
```

## 2、target_link_directories
```
path/to/onnxruntime-static-lib/staticlib
```

## 3、target_link_libraries
```
Release/onnxruntime_session.lib
Release/onnxruntime_optimizer.lib
Release/onnxruntime_providers.lib
Release/onnxruntime_util.lib
Release/onnxruntime_framework.lib
Release/onnxruntime_graph.lib
Release/onnxruntime_mlas.lib
Release/onnxruntime_common.lib
Release/onnxruntime_flatbuffers.lib
Release/onnx_test_data_proto.lib
external/onnx/Release/onnx.lib
external/onnx/Release/onnx_proto.lib
external/protobuf/cmake/Release/libprotobuf-lite.lib
external/re2/Release/re2.lib
external/abseil-cpp/absl/base/Release/absl_base.lib
external/abseil-cpp/absl/base/Release/absl_throw_delegate.lib
external/abseil-cpp/absl/container/Release/absl_raw_hash_set.lib
external/abseil-cpp/absl/hash/Release/absl_hash.lib
external/abseil-cpp/absl/hash/Release/absl_city.lib
external/abseil-cpp/absl/hash/Release/absl_low_level_hash.lib
```

## 4、include the .h file in your .cpp file
```
#include <session/onnxruntime_cxx_api.h>
```