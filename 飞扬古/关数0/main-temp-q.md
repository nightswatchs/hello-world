1. main中一共调用了几个函数
  2. print_time
  2. read_file:
  3. read_file:
  4. search_route(topo(输入),edge_num(边个数),demand(输入文件))
  5. write_result
  6. release_buff
  7. release_buff
2. 他们的值都是什么意思？
  3. read_file：
    4. topo:目标数据，buff就是数组,数据为***被逗号分割的行数据***
    5. 5000：最大数据？\
    6. topo_file:所要读取的
    7. edge_num:实际个数
  4. write_result:
    5. filename:输出的文件名
    6. g_result：输出格式的字符串(真他娘的是保姆啊)
3. main中的函数两个参数是什么意思？
  4. topo_file
  5. demand_file
  6. 就是和python是一样的结果。文件名为第一个！哈哈哈哈哈哈哈哈
4. search_route的返回值跑到哪里了？直接调用了输出函数？
  5. g_result.
  6. record_result()
5. g_result在哪儿
6. search_route需要输出到控制台吗？
7. record_result事干什么的
  8. 将数字输出到字符串中。就是g_result


因此这个route函数只要将得到的字符串分割为数据，处理数据，调用record_result就可以了
total:14
