include_directories ("./")

add_library(ebml_build
    src/Debug.cpp 
	src/EbmlBinary.cpp 
	src/EbmlContexts.cpp 
	src/EbmlCrc32.cpp 
	src/EbmlDate.cpp 
	src/EbmlDummy.cpp 
	src/EbmlElement.cpp 
	src/EbmlFloat.cpp 
	src/EbmlHead.cpp 
	src/EbmlMaster.cpp 
	src/EbmlSInteger.cpp 
	src/EbmlStream.cpp 
	src/EbmlString.cpp 
	src/EbmlSubHead.cpp 
	src/EbmlUInteger.cpp 
	src/EbmlUnicodeString.cpp 
	src/EbmlVersion.cpp 
	src/EbmlVoid.cpp 
	src/IOCallback.cpp 
	src/MemIOCallback.cpp 
	src/MemReadIOCallback.cpp 
	src/SafeReadIOCallback.cpp 
	src/StdIOCallback.cpp
)
