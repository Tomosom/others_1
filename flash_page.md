
<pre>
<code>
- delphi@delphi-vm:~$ gdb      // 启动
- (gdb) `attach <font color=red>pid</font>            // 链接到目标进程, 链接成功后bbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbb
                               // 目标进程将停止执行
- (gdb) continue               // 恢复执行
</code>
</pre>


<pre>
- (gdb) `attach pid            // 链接到目标进程, 链接成功后aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa
                               // 目标进程将停止执行
- (gdb) continue               // 恢复执行
</pre>




<pre>
Usage: grep [OPTION] . . .PATTERN [FILE] . . .
</pre>





<pre>
- delphi@delphi-vm:~$ gdb      // 启动
- (gdb) `attach <font color=red>pid</font>            // 链接到目标进程, 链接成功后
                               // 目标进程将停止执行
- (gdb) continue               // 恢复执行
</pre>



:::alert-light
<pre>
- delphi@delphi-vm:~$ gdb      // 启动
- (gdb) `attach <font color=red>pid</font>            // 链接到目标进程, 链接成功后
                               // 目标进程将停止执行
- (gdb) continue               // 恢复执行
</pre>
:::

:::alert-light

`-` delphi@delphi-vm:~$ gdb      // 启动
`-` (gdb) `` ` ``attach pid             // 链接到目标进程, 链接成功后
                               // 目标进程将停止执行
`-` (gdb) continue               // 恢复执行

:::

:::alert-light
```
- delphi@delphi-vm:~$ gdb      // 启动
- (gdb) `attach pid             // 链接到目标进程, 链接成功后
                               // 目标进程将停止执行
- (gdb) continue               // 恢复执行
```
:::


:::alert-light

`-` delphi@delphi-vm:~$ gdb      // 启动
`-` (gdb) `` ` ``attach pid             // 链接到目标进程, 链接成功后
                               // 目标进程将停止执行
`-` (gdb) continue               // 恢复执行

:::


<style type="text/css">
#left{
float:left; width:240px; height:500px; background:#0C9;
}
#center{
float:left; width:240px; height:500px; background:#06C;
}
#right{
float:left; width:240px; height:500px; background:#933;
}
</style>
<body>
<div id="left" >
左

```c
int main()
{
    return 0;
}
```

</div>
<div id="center" style="">
中

```c
int main()
{
    return 0;
}
```

</div>
<div id="right" >
右

```c
int main()
{
    return 0;
}
```

</div>

</body>