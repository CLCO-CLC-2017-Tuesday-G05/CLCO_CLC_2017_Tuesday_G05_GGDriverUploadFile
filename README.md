# CLCO_CLC_2017_Tuesday_G05_GGDriverUploadFile
# Nguyen Quoc Tinh-14110422; Nguyen Tuan Kiet-14110348; Duong Ngoc Hao-14110385
# Hướng dẫn fix lỗi:
# 1. 400:
# Khi chạy project, nếu găp lỗi 400 thì fix như sau:
# - Servers -> Chọn server bạn đang chạy ( Tomcat v...)-->
#    -> server.xml -> thêm allowCasualMultipartParsing="true" vào Context docBase="UploadFile"... path="/UploadFile"..."/>
# 2. 500:
# Khi chọn upload nếu gặp lỗi 500 thì fix như sau:
#  - Project Properties -> Deployment Assembly -> Add -> Java Build Path Entries -> chọn thư viện và add
