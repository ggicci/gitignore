# gitignore

Get template gitignore file from shell on your terminal.

## Usage

```text
Usage: gitignore <template>

Examples:
  gitignore python
  gitignore go > .gitignore
```

**Example 1**:

```shell
gitignore java
```

**Output 1**:

```
# Compiled class file
*.class

# Log file
*.log

# BlueJ files
*.ctxt

# Mobile Tools for Java (J2ME)
.mtj.tmp/

# Package Files #
*.jar
*.war
*.nar
*.ear
*.zip
*.tar.gz
*.rar

# virtual machine crash logs, see http://www.java.com/en/download/help/error_hotspot.xml
hs_err_pid*
```

**Example 2**:

```shell
gitignore fuck
```

**Output 2**:

```text
gitignore: fuck not found

Available:
Actionscript Ada Agda Android Anjuta Ansible AppEngine AppceleratorTitanium ArchLinuxPackages Archives AtmelStudio Autotools Backup Bazaar Bazel Bitrix BricxCC C C++ CFWheels CMake CUDA CVS CakePHP Calabash ChefCookbook Cloud9 CodeIgniter CodeKit CodeSniffer CommonLisp Composer Concrete5 Coq Cordova CraftCMS D DM Dart DartEditor Delphi Diff Dreamweaver Dropbox Drupal Drupal7 EPiServer Eagle Eclipse EiffelStudio Elisp Elixir Elm Emacs Ensime Erlang Espresso Exercism ExpressionEngine ExtJs Fancy Finale FlexBuilder ForceDotCom FuelPHP GNOMEShellExtension GPG GWT Gcov GitBook Go Godot Gradle Grails Haskell Hugo IAR_EWARM IGORPro Idris Images InforCMS JBoss JBoss4 JBoss6 JDeveloper JENKINS_HOME JEnv Java Jekyll JetBrains Jigsaw Joomla Julia JupyterNotebooks KDevelop4 Kate Kentico KiCad Kohana LabVIEW Laravel Lazarus Leiningen LemonStand LibreOffice Lilypond Linux Lithium Logtalk Lua LyX MATLAB Magento Magento1 Magento2 Maven Mercurial Mercury MetaProgrammingSystem Metals Meteor MicrosoftOffice ModelSim Momentics MonoDevelop NWjs Nanoc NetBeans Nikola Nim Ninja Node NotepadPP OCaml Objective-C Opa OpenCart OpenSSL OracleForms Otto PSoCCreator Packer Patch Perl Phalcon Phoenix Pimcore PlayFramework Plone Prestashop Processing PuTTY Puppet PureScript Python Qooxdoo Qt R ROS Racket Rails Raku Red Redcar Redis RhodesRhomobile Ruby Rust SAM SBT SCons SVN Sass Scala Scheme Scrivener Sdcc SeamGen SketchUp SlickEdit Smalltalk Snap Splunk Stata Stella SublimeText SugarCRM Swift Symfony SymphonyCMS SynopsysVCS Tags TeX Terraform TextMate Textpattern ThinkPHP TortoiseGit TurboGears2 Typo3 Umbraco Unity UnrealEngine VVVV Vagrant Vim VirtualEnv Virtuoso VisualStudio VisualStudioCode Vue Waf WebMethods Windows WordPress Xcode Xilinx XilinxISE Xojo Yeoman Yii ZendFramework Zephir esp-idf macOS
```
