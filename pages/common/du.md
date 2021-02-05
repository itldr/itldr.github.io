du
===

&#x663E;&#x793A;&#x6BCF;&#x4E2A;&#x6587;&#x4EF6;&#x548C;&#x76EE;&#x5F55;&#x7684;&#x78C1;&#x76D8;&#x4F7F;&#x7528;&#x7A7A;&#x95F4;

## &#x8865;&#x5145;&#x8BF4;&#x660E;

**du&#x547D;&#x4EE4;** &#x4E5F;&#x662F;&#x67E5;&#x770B;&#x4F7F;&#x7528;&#x7A7A;&#x95F4;&#x7684;&#xFF0C;&#x4F46;&#x662F;&#x4E0E;df&#x547D;&#x4EE4;&#x4E0D;&#x540C;&#x7684;&#x662F;Linux du&#x547D;&#x4EE4;&#x662F;&#x5BF9;&#x6587;&#x4EF6;&#x548C;&#x76EE;&#x5F55;&#x78C1;&#x76D8;&#x4F7F;&#x7528;&#x7684;&#x7A7A;&#x95F4;&#x7684;&#x67E5;&#x770B;&#xFF0C;&#x8FD8;&#x662F;&#x548C;df&#x547D;&#x4EE4;&#x6709;&#x4E00;&#x4E9B;&#x533A;&#x522B;&#x7684;&#x3002;

### &#x8BED;&#x6CD5;

```shell
du [&#x9009;&#x9879;][&#x6587;&#x4EF6;]
```

### &#x9009;&#x9879;

```shell
-a, --all                              &#x663E;&#x793A;&#x76EE;&#x5F55;&#x4E2D;&#x4E2A;&#x522B;&#x6587;&#x4EF6;&#x7684;&#x5927;&#x5C0F;&#x3002;
-B, --block-size=&#x5927;&#x5C0F;                  &#x4F7F;&#x7528;&#x6307;&#x5B9A;&#x5B57;&#x8282;&#x6570;&#x7684;&#x5757;
-b, --bytes                            &#x663E;&#x793A;&#x76EE;&#x5F55;&#x6216;&#x6587;&#x4EF6;&#x5927;&#x5C0F;&#x65F6;&#xFF0C;&#x4EE5;byte&#x4E3A;&#x5355;&#x4F4D;&#x3002;
-c, --total                            &#x9664;&#x4E86;&#x663E;&#x793A;&#x4E2A;&#x522B;&#x76EE;&#x5F55;&#x6216;&#x6587;&#x4EF6;&#x7684;&#x5927;&#x5C0F;&#x5916;&#xFF0C;&#x540C;&#x65F6;&#x4E5F;&#x663E;&#x793A;&#x6240;&#x6709;&#x76EE;&#x5F55;&#x6216;&#x6587;&#x4EF6;&#x7684;&#x603B;&#x548C;&#x3002;
-D, --dereference-args                 &#x663E;&#x793A;&#x6307;&#x5B9A;&#x7B26;&#x53F7;&#x94FE;&#x63A5;&#x7684;&#x6E90;&#x6587;&#x4EF6;&#x5927;&#x5C0F;&#x3002;
-H, --si                               &#x4E0E;-h&#x53C2;&#x6570;&#x76F8;&#x540C;&#xFF0C;&#x4F46;&#x662F;K&#xFF0C;M&#xFF0C;G&#x662F;&#x4EE5;1000&#x4E3A;&#x6362;&#x7B97;&#x5355;&#x4F4D;&#x3002;
-h, --human-readable                   &#x4EE5;K&#xFF0C;M&#xFF0C;G&#x4E3A;&#x5355;&#x4F4D;&#xFF0C;&#x63D0;&#x9AD8;&#x4FE1;&#x606F;&#x7684;&#x53EF;&#x8BFB;&#x6027;&#x3002;
-k, --kilobytes                        &#x4EE5;KB(1024bytes)&#x4E3A;&#x5355;&#x4F4D;&#x8F93;&#x51FA;&#x3002;
-l, --count-links                      &#x91CD;&#x590D;&#x8BA1;&#x7B97;&#x786C;&#x4EF6;&#x94FE;&#x63A5;&#x7684;&#x6587;&#x4EF6;&#x3002;
-m, --megabytes                        &#x4EE5;MB&#x4E3A;&#x5355;&#x4F4D;&#x8F93;&#x51FA;&#x3002;
-L<&#x7B26;&#x53F7;&#x94FE;&#x63A5;>, --dereference<&#x7B26;&#x53F7;&#x94FE;&#x63A5;>  &#x663E;&#x793A;&#x9009;&#x9879;&#x4E2D;&#x6240;&#x6307;&#x5B9A;&#x7B26;&#x53F7;&#x94FE;&#x63A5;&#x7684;&#x6E90;&#x6587;&#x4EF6;&#x5927;&#x5C0F;&#x3002;
-P, --no-dereference                   &#x4E0D;&#x8DDF;&#x968F;&#x4EFB;&#x4F55;&#x7B26;&#x53F7;&#x94FE;&#x63A5;(&#x9ED8;&#x8BA4;)
-0, --null                             &#x5C06;&#x6BCF;&#x4E2A;&#x7A7A;&#x884C;&#x89C6;&#x4F5C;0 &#x5B57;&#x8282;&#x800C;&#x975E;&#x6362;&#x884C;&#x7B26;
-S, --separate-dirs                    &#x663E;&#x793A;&#x4E2A;&#x522B;&#x76EE;&#x5F55;&#x7684;&#x5927;&#x5C0F;&#x65F6;&#xFF0C;&#x5E76;&#x4E0D;&#x542B;&#x5176;&#x5B50;&#x76EE;&#x5F55;&#x7684;&#x5927;&#x5C0F;&#x3002;
-s, --summarize                        &#x4EC5;&#x663E;&#x793A;&#x603B;&#x8BA1;&#xFF0C;&#x53EA;&#x5217;&#x51FA;&#x6700;&#x540E;&#x52A0;&#x603B;&#x7684;&#x503C;&#x3002;
-x, --one-file-xystem                  &#x4EE5;&#x4E00;&#x5F00;&#x59CB;&#x5904;&#x7406;&#x65F6;&#x7684;&#x6587;&#x4EF6;&#x7CFB;&#x7EDF;&#x4E3A;&#x51C6;&#xFF0C;&#x82E5;&#x9047;&#x4E0A;&#x5176;&#x5B83;&#x4E0D;&#x540C;&#x7684;&#x6587;&#x4EF6;&#x7CFB;&#x7EDF;&#x76EE;&#x5F55;&#x5219;&#x7565;&#x8FC7;&#x3002;
-X<&#x6587;&#x4EF6;>, --exclude-from=<&#x6587;&#x4EF6;>        &#x5728;<&#x6587;&#x4EF6;>&#x6307;&#x5B9A;&#x76EE;&#x5F55;&#x6216;&#x6587;&#x4EF6;&#x3002;
--apparent-size                        &#x663E;&#x793A;&#x8868;&#x9762;&#x7528;&#x91CF;&#xFF0C;&#x800C;&#x5E76;&#x975E;&#x662F;&#x78C1;&#x76D8;&#x7528;&#x91CF;&#xFF1B;&#x867D;&#x7136;&#x8868;&#x9762;&#x7528;&#x91CF;&#x901A;&#x5E38;&#x4F1A;&#x5C0F;&#x4E00;&#x4E9B;&#xFF0C;&#x4F46;&#x6709;&#x65F6;&#x5B83;&#x4F1A;&#x56E0;&#x4E3A;&#x7A00;&#x758F;&#x6587;&#x4EF6;&#x95F4;&#x7684;"&#x6D1E;"&#x3001;&#x5185;&#x90E8;&#x788E;&#x7247;&#x3001;&#x975E;&#x76F4;&#x63A5;&#x5F15;&#x7528;&#x7684;&#x5757;&#x7B49;&#x539F;&#x56E0;&#x800C;&#x53D8;&#x5927;&#x3002;
--files0-from=F                        &#x8BA1;&#x7B97;&#x6587;&#x4EF6;F&#x4E2D;&#x4EE5;NUL&#x7ED3;&#x5C3E;&#x7684;&#x6587;&#x4EF6;&#x540D;&#x5BF9;&#x5E94;&#x5360;&#x7528;&#x7684;&#x78C1;&#x76D8;&#x7A7A;&#x95F4;&#x5982;&#x679C;F&#x7684;&#x503C;&#x662F;"-"&#xFF0C;&#x5219;&#x4ECE;&#x6807;&#x51C6;&#x8F93;&#x5165;&#x8BFB;&#x5165;&#x6587;&#x4EF6;&#x540D;
--exclude=<&#x76EE;&#x5F55;&#x6216;&#x6587;&#x4EF6;>                 &#x7565;&#x8FC7;&#x6307;&#x5B9A;&#x7684;&#x76EE;&#x5F55;&#x6216;&#x6587;&#x4EF6;&#x3002;
--max-depth=N                          &#x663E;&#x793A;&#x76EE;&#x5F55;&#x603B;&#x8BA1;(&#x4E0E;--all &#x4E00;&#x8D77;&#x4F7F;&#x7528;&#x8BA1;&#x7B97;&#x6587;&#x4EF6;)&#x5F53;N&#x4E3A;&#x6307;&#x5B9A;&#x6570;&#x503C;&#x65F6;&#x8BA1;&#x7B97;&#x6DF1;&#x5EA6;&#x4E3A;N&#xFF0C;&#x7B49;&#x4E8E;0&#x65F6;&#x7B49;&#x540C;--summarize
--si                                   &#x7C7B;&#x4F3C;-h&#xFF0C;&#x4F46;&#x5728;&#x8BA1;&#x7B97;&#x65F6;&#x4F7F;&#x7528;1000 &#x4E3A;&#x57FA;&#x5E95;&#x800C;&#x975E;1024
--time                                 &#x663E;&#x793A;&#x76EE;&#x5F55;&#x6216;&#x8BE5;&#x76EE;&#x5F55;&#x5B50;&#x76EE;&#x5F55;&#x4E0B;&#x6240;&#x6709;&#x6587;&#x4EF6;&#x7684;&#x6700;&#x540E;&#x4FEE;&#x6539;&#x65F6;&#x95F4;
--time=WORD                            &#x663E;&#x793A;WORD&#x65F6;&#x95F4;&#xFF0C;&#x800C;&#x975E;&#x4FEE;&#x6539;&#x65F6;&#x95F4;&#xFF1A;atime&#xFF0C;access&#xFF0C;use&#xFF0C;ctime &#x6216;status
--time-style=&#x6837;&#x5F0F;                      &#x6309;&#x7167;&#x6307;&#x5B9A;&#x6837;&#x5F0F;&#x663E;&#x793A;&#x65F6;&#x95F4;(&#x6837;&#x5F0F;&#x89E3;&#x91CA;&#x89C4;&#x5219;&#x540C;"date"&#x547D;&#x4EE4;)&#xFF1A;full-iso&#xFF0C;long-iso&#xFF0C;iso&#xFF0C;+FORMAT
--help                                 &#x663E;&#x793A;&#x6B64;&#x5E2E;&#x52A9;&#x4FE1;&#x606F;&#x5E76;&#x9000;&#x51FA;
--version                              &#x663E;&#x793A;&#x7248;&#x672C;&#x4FE1;&#x606F;&#x5E76;&#x9000;&#x51FA;
```

### &#x5B9E;&#x4F8B;

&#x6587;&#x4EF6;&#x4ECE;&#x5927;&#x5230;&#x5C0F;&#x6392;&#x5E8F;
```
ubuntu@VM-0-14-ubuntu:~/git-work/linux-command$ du -sh * |sort -rh
2.9M    command
1.9M    assets
148K    template
72K     package-lock.json
52K     dist
28K     build
16K     README.md
4.0K    renovate.json
4.0K    package.json
4.0K    LICENSE
```

&#x53EA;&#x663E;&#x793A;&#x5F53;&#x524D;&#x76EE;&#x5F55;&#x4E0B;&#x5B50;&#x76EE;&#x5F55;&#x7684;&#x5927;&#x5C0F;&#x3002;

```shell
ubuntu@VM-0-14-ubuntu:~/git-work/linux-command$ du -sh ./*/
1.9M    ./assets/
28K     ./build/
2.9M    ./command/
52K     ./dist/
148K    ./template/
```

&#x67E5;&#x770B;&#x6307;&#x5B9A;&#x76EE;&#x5F55;&#x4E0B;&#x6587;&#x4EF6;&#x6240;&#x5360;&#x7684;&#x7A7A;&#x95F4;&#xFF1A;

```shell
ubuntu@VM-0-14-ubuntu:~/git-work/linux-command/assets$ du ./*
144     ./alfred.png
452     ./chrome-extensions.gif
4       ./dash-icon.png
1312    ./Linux.gif
16      ./qr.png
```

&#x53EA;&#x663E;&#x793A;&#x603B;&#x548C;&#x7684;&#x5927;&#x5C0F;:

```shell
ubuntu@VM-0-14-ubuntu:~/git-work/linux-command/assets$ du -s .
1932    .
```

&#x663E;&#x793A;&#x603B;&#x548C;&#x7684;&#x5927;&#x5C0F;&#x4E14;&#x6613;&#x8BFB;:

```shell
ubuntu@VM-0-14-ubuntu:~/git-work/linux-command/assets$ du -sh .
1.9M    .
```

<!-- Linux&#x547D;&#x4EE4;&#x884C;&#x641C;&#x7D22;&#x5F15;&#x64CE;&#xFF1A;https://jaywcjlove.github.io/linux-command/ -->