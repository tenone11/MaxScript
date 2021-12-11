# Usefule_Scripts
Some useful commands for me
- MS Check and select no smoothgroup face
检测3ds Max中没有光滑组的面
- MS_UV_Vertex_Center
寻找UV两点的中心
- Maya2022可以使用CMD进行ui>py
C:\progra~1\Autodesk\Maya2022\bin3\pyside2-uic.exe your_file_name.ui -o your_file_name.py
- web爬虫有些element只有点开才能看见，需要用到一些js
description_children_by_xpath = driver.find_elements_by_xpath(".//*")
attrs = description_children_by_xpath.execute_script('var items = {}; for (index = 0; index < arguments[0].attributes.length; ++index) { items[arguments[0].attributes[index].name] =arguments[0].attributes[index].value }; return items;',all_children_by_xpath[0])
print(attrs)
