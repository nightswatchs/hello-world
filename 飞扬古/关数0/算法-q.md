* 得到的是一行行的内容，分割然后把信息存储在链表图中。这个算法怎么写
  * 分割，得到一个数组string_of_file
  * 将字符串变成数字串int_of_file
  * 得到信息后,存储在边集中
    * 得到出度：add_to_vex_out=.firstout,while(!null).什么鬼如果为null修改，不是null，(while)就可以了，判断是不是存在这个点了？
    * 初始化自己，两个null剩下的已经给出了
    * 得到进入的点，相同的方法，
* 起个什么名字呢？
  * add_to_vex_in

* arc中相同起点的量是哪一个？headlink
* arc中相同终点的量是哪一个？taillink
* c++分割字符串的函数是？
  * strtok(char \*str, const char \*delim);
  * 从str开始一个个被分割的串，没有的话返回null
  * `p = strtok(s,d);
    while(p){
      printf("%s\n",p);
      p=strtok(NULL,d);
    }`//
  * 注意：开始要有s，以后就是null
* c++将字符串变为int的函数是哪一个？
  * atoi()//转换为int
* 有没有注意c++和C不一样的地方啊？
  * using namespace std;
* 反正这个边使可以直接用数组表示的，但是点呢，如果不连续呢？

##读取要求文件：
* 方法和上面的一样吧，
