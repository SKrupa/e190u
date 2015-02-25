EXE=bgfg_segm

all: $(EXE)

$(EXE): bgfg_segm.cpp
	g++ $< -lopencv_core -lopencv_imgproc -lopencv_highgui -lopencv_video -lopencv_gpu -o $@
