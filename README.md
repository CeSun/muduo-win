# calm: muduo for win

原本的muduo-win头文件引用混乱，vcxproj的项目配置也有一些问题，不能直接编译，我稍微修改了一下，可以直接使用vs2017进行编译了。

库具体没有测试，正在学习中。

以下是源readme。

# calm

excerpts from muduo:https://github.com/chenshuo/muduo
Change it to windows,use C++11.
## How to use
### Environment
Use virtual studio 2017, which can support C++11 std::thread std::mutex and so on.
### Build
Download from github<br/>
`git clone git@github.com:kevin-gjm/calm.git`<br/>
The sln file in src/build/calm/calm.sln <br\>
build x86 Debug/Release<br/>

The protobuf include and lib are in directory  `src/3rdParty`.You may add it.

## PS
Not separate the base and net library from the solution.You may do it by yourself.
