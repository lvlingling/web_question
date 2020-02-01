# 基础知识

## 例举3种强制类型转换和2种隐式类型转换

参考：[http://www.imooc.com/article/281312](http://www.imooc.com/article/281312)

强制:（parseInt,parseFloat,Number,Boolean）

隐式: 

<table>
  <thead>
    <tr>
      <th style="text-align:left"></th>
      <th style="text-align:left"></th>
      <th style="text-align:left"></th>
      <th style="text-align:left"></th>
      <th style="text-align:left"></th>
      <th style="text-align:left"></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">==</td>
      <td style="text-align:left">+(&#x8F6C;&#x5316;&#x4E3A;&#x6570;&#x5B57;&#xFF0C;&#x548C;Number&#x5DEE;&#x4E0D;&#x591A;)</td>
      <td
      style="text-align:left">
        <p>if()</p>
        <p>for()</p>
        <p>while()</p>
        </td>
        <td style="text-align:left">!(&#x8F6C;&#x5316;&#x4E3A;&#x5E03;&#x5C14;&#x503C;)</td>
        <td style="text-align:left">
          <p></p>
          <p>&#x903B;&#x8F91;&#x975E;||&#x548C;&#x903B;&#x8F91;&#x4E0E;&amp;&amp;
            <br
            />(&#x4F1A;&#x5BF9;&#x7B2C;&#x4E00;&#x4E2A;&#x503C;&#x8FDB;&#x884C;&#x5E03;&#x5C14;&#x5224;&#x65AD;&#xFF0C;||&#x7B2C;&#x4E00;&#x4E2A;&#x4E3A;false&#xFF0C;&#x8FD4;&#x56DE;&#x7B2C;&#x4E8C;&#x4E2A;&#x503C;&#xFF0C;&amp;&amp;&#x7B2C;&#x4E00;&#x4E2A;&#x4E3A;false&#xFF0C;&#x8FD4;&#x56DE;&#x7B2C;&#x4E00;&#x4E2A;&#x503C;&#x3002;)</p>
          <p>console.log(&quot;hello&quot; || &quot;love&quot;); //&#x8F93;&#x51FA;&#xFF1A;hello
            <br
            />console.log(&quot;&quot; || &quot;love&quot;); //&#x8F93;&#x51FA;&#xFF1A;love</p>
          <p>console.log(1 &amp;&amp; &quot;love&quot;); //&#x8F93;&#x51FA;&#xFF1A;love
            <br
            />console.log(0 &amp;&amp; &quot;love&quot;); //&#x8F93;&#x51FA;&#xFF1A;0</p>
        </td>
        <td style="text-align:left">
          <p></p>
          <p>
            <br />&#x4E09;&#x5143;&#x8868;&#x8FBE;&#x5F0F;</p>
        </td>
    </tr>
  </tbody>
</table>## 数组实现去重

Yes, after a few months we finally found the answer. Sadly, Mike is on vacations right now so I'm afraid we are not able to provide the answer at this point.

## 字符串的方法

<table>
  <thead>
    <tr>
      <th style="text-align:left">&#x5B57;&#x7B26;&#x4E32;&#x622A;&#x53D6;</th>
      <th style="text-align:left">&#x68C0;&#x7D22;</th>
      <th style="text-align:left">&#x5927;&#x5C0F;&#x5199;</th>
      <th style="text-align:left">&#x5B57;&#x7B26;&#x4E32;&#x5BF9;&#x8C61;&#x7684;&#x65B9;&#x6CD5;</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">
        <p>1&#x3001;slice() //stringObject.slice(start,end)</p>
        <p>2&#x3001;substring() //&#x540C;slice()&#x5B8C;&#x5168;&#x4E00;&#x6837;&#xFF0C;&#x533A;&#x522B;&#x53EA;&#x5728;&#x4E8E;&#x9047;&#x5230;&#x8D1F;&#x6570;&#x65F6;&#xFF0C;&#x81EA;&#x52A8;&#x5C06;&#x53C2;&#x6570;&#x8F6C;&#x6362;&#x4E3A;0.&#x628A;&#x8F83;&#x5C0F;&#x7684;&#x6570;&#x4F5C;&#x4E3A;&#x5F00;&#x59CB;&#x4F4D;&#x7F6E;&#xFF0C;&#x8F83;&#x5927;&#x7684;&#x6570;&#x4F5C;&#x4E3A;&#x7ED3;&#x675F;&#x4F4D;&#x7F6E;&#x3002;</p>
        <p>3&#x3001;substr()//stringObiect.substr(start,len)</p>
      </td>
      <td style="text-align:left">
        <p><code>let a=&apos;123abc&apos;;</code>
        </p>
        <p><code>a.charAt(0)//1</code>
        </p>
        <p><code>a.charCodeAt(0)//49</code>
        </p>
        <p><code>a.indexOf(&apos;c&apos;)//5</code>
        </p>
        <p><code>a.lastIndexOf(&apos;2&apos;)//1</code>
        </p>
      </td>
      <td style="text-align:left">toUpperCase()
        <br />toLowerCase()</td>
      <td style="text-align:left">
        <p>split() //&#x53D8;&#x6210;&#x6570;&#x7EC4;</p>
        <p>replace()</p>
      </td>
    </tr>
  </tbody>
</table>## 数组的方法

Yes, after a few months we finally found the answer. Sadly, Mike is on vacations right now so I'm afraid we are not able to provide the answer at this point.

## [forEach、for in、for of 三者对比](https://www.cnblogs.com/theblogs/p/10520590.html)



