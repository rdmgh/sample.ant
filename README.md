# sample.ant
```
https://answers.splunk.com/answers/11350/2-searches-1-chart.html
<target name="hash">
  <checksum todir="x" format="MD5SUM" totalproperty="sum.of.all">
    <fileset dir="x"/>
  </checksum>
  <echo>${sum.of.all}</echo>
</target>

https://stackoverflow.com/questions/8599216/generate-checksum-for-directories-using-ant-build-command

<target name="minor">
     <propertyfile file="build_info.properties">
         <entry key="build.minor.number" type="int" operation="+" value="1" pattern="00" />
         <entry key="build.revision.number" type="int" value="0" pattern="00" />
     </propertyfile>
</target>

https://stackoverflow.com/questions/3439876/use-ant-to-update-build-number-and-inject-into-source-code

https://www.mkyong.com/jsf2/jsf-2-0-and-resource-bundles-example/

http://llbit.se/?p=1876

https://ant.apache.org/manual/Tasks/move.html

https://stackoverflow.com/questions/5220271/multiple-renaming-using-ant-script
```
