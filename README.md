mkdir -p layer/python

pip install pymysql cryptography -t layer/python

cd layer
zip -r ../pymysql_layer.zip .
cd ..
