## How do you design MQTT topics and payloads for smart washing machine

1. สถานะเครื่องซักผ้า
    - topic:v1cdti/app/get/1212312121/model-01/sn-001/
    - payload
        - {"STATUS": "POWER ON|START|STOP|FINISHED|POWERED OFF"}
        - {"STATUS": "WASH|SPIN|DRAINED"}
1. เซนเซอร์ภายในเครื่องซักผ้า
    - topic:v1cdti/hw/get/6310301011/model-01/sn-001
    - payload
        - {"temperature": "25.2"}
        - {"้speed": "100"}
        - {"Perssure": "10"}
        - {"Fabric": "0"|"1"}
        - {"Weight": "10"}
        - {"filter_clogging": "0"|"1"}
        - {"water_flow": "0.425"}
        - {"Water_level": "1"}
        - {"Foam_detection": "0"|"1"}
        - {"้defacts": "0"|"1"}
        - {"้co2": "3ppm"}
        - {"้Air_quality": "0"|"1"}
        - {"้imbalance": "0"|"1"}
        - {"้vibration": "0"|"1"}
        - {"Noise_anomary": "60db"}
        - {"้Material": "0"|"1"}
        - {"้Air_pressure": "10"}
        - {"้humidity": "20"}
        
        

       #get ค่า ณ ตอนนั้น
       #set ค่าที่อยากให้เป็น
        

 1. เซนเซอร์ภายนอกเครื่องซักผ้า
    - topic:v1cdti/app/get/6310301011/model-02/sn-001
    - payload
        - {"3D_position": "3"}
        - {"Touch": "0"|"1"}
        - {"Lid": "0"|"1"}
        - {"Voise_command": "30db"}
        - {"count_people": "5"}
        - {"track_people": "3"}



