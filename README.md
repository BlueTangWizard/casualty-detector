1.  
    cd casualty-detector


2.  Install the OpenCV libraries:

    bash install_requirements.sh

3.  Run detection:

    python3 detect.py


By default, this uses the ```mobilenet_ssd_v2_coco_quant_postprocess_edgetpu.tflite``` model.

You can change the model and the labels file using flags ```--model``` and ```--labels```.
