# api documentation for  [argparse (v1.0.9)](https://github.com/nodeca/argparse#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-argparse.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-argparse) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-argparse.svg)](https://travis-ci.org/npmdoc/node-npmdoc-argparse)
#### Very powerful CLI arguments parser. Native port of argparse - python's options parsing library

[![NPM](https://nodei.co/npm/argparse.png?downloads=true)](https://www.npmjs.com/package/argparse)

[![apidoc](https://npmdoc.github.io/node-npmdoc-argparse/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-argparse_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-argparse/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-argparse/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-argparse/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/nodeca/argparse/issues"
    },
    "contributors": [
        {
            "name": "Eugene Shkuropat"
        },
        {
            "name": "Paul Jacobson"
        }
    ],
    "dependencies": {
        "sprintf-js": "~1.0.2"
    },
    "description": "Very powerful CLI arguments parser. Native port of argparse - python's options parsing library",
    "devDependencies": {
        "eslint": "^2.13.1",
        "istanbul": "^0.4.5",
        "mocha": "^3.1.0",
        "ndoc": "^5.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "73d83bc263f86e97f8cc4f6bae1b0e90a7d22c86",
        "tarball": "https://registry.npmjs.org/argparse/-/argparse-1.0.9.tgz"
    },
    "files": [
        "index.js",
        "lib/"
    ],
    "gitHead": "acb39f2d726b90d2eadf9e6574a938d6250ad248",
    "homepage": "https://github.com/nodeca/argparse#readme",
    "keywords": [
        "cli",
        "parser",
        "argparse",
        "option",
        "args"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "vitaly",
            "email": "vitaly@rcdesign.ru"
        }
    ],
    "name": "argparse",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/nodeca/argparse.git"
    },
    "scripts": {
        "test": "make test"
    },
    "version": "1.0.9"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module argparse](#apidoc.module.argparse)
1.  [function <span class="apidocSignatureSpan">argparse.</span>Action (options)](#apidoc.element.argparse.Action)
1.  [function <span class="apidocSignatureSpan">argparse.</span>ArgumentDefaultsHelpFormatter (options)](#apidoc.element.argparse.ArgumentDefaultsHelpFormatter)
1.  [function <span class="apidocSignatureSpan">argparse.</span>ArgumentParser (options)](#apidoc.element.argparse.ArgumentParser)
1.  [function <span class="apidocSignatureSpan">argparse.</span>ArgumentParser.super_ (options)](#apidoc.element.argparse.ArgumentParser.super_)
1.  [function <span class="apidocSignatureSpan">argparse.</span>HelpFormatter (options)](#apidoc.element.argparse.HelpFormatter)
1.  [function <span class="apidocSignatureSpan">argparse.</span>Namespace (options)](#apidoc.element.argparse.Namespace)
1.  [function <span class="apidocSignatureSpan">argparse.</span>RawDescriptionHelpFormatter (options)](#apidoc.element.argparse.RawDescriptionHelpFormatter)
1.  [function <span class="apidocSignatureSpan">argparse.</span>RawTextHelpFormatter (options)](#apidoc.element.argparse.RawTextHelpFormatter)
1.  object <span class="apidocSignatureSpan">argparse.</span>Action.prototype
1.  object <span class="apidocSignatureSpan">argparse.</span>ArgumentDefaultsHelpFormatter.prototype
1.  object <span class="apidocSignatureSpan">argparse.</span>ArgumentParser.prototype
1.  object <span class="apidocSignatureSpan">argparse.</span>ArgumentParser.super_.prototype
1.  object <span class="apidocSignatureSpan">argparse.</span>Const
1.  object <span class="apidocSignatureSpan">argparse.</span>HelpFormatter.prototype
1.  object <span class="apidocSignatureSpan">argparse.</span>Namespace.prototype
1.  object <span class="apidocSignatureSpan">argparse.</span>RawDescriptionHelpFormatter.prototype
1.  object <span class="apidocSignatureSpan">argparse.</span>RawTextHelpFormatter.prototype
1.  object <span class="apidocSignatureSpan">argparse.</span>utils

#### [module argparse.Action](#apidoc.module.argparse.Action)
1.  [function <span class="apidocSignatureSpan">argparse.</span>Action (options)](#apidoc.element.argparse.Action.Action)

#### [module argparse.Action.prototype](#apidoc.module.argparse.Action.prototype)
1.  [function <span class="apidocSignatureSpan">argparse.Action.prototype.</span>call ()](#apidoc.element.argparse.Action.prototype.call)
1.  [function <span class="apidocSignatureSpan">argparse.Action.prototype.</span>getName ()](#apidoc.element.argparse.Action.prototype.getName)
1.  [function <span class="apidocSignatureSpan">argparse.Action.prototype.</span>isOptional ()](#apidoc.element.argparse.Action.prototype.isOptional)
1.  [function <span class="apidocSignatureSpan">argparse.Action.prototype.</span>isPositional ()](#apidoc.element.argparse.Action.prototype.isPositional)

#### [module argparse.ArgumentDefaultsHelpFormatter](#apidoc.module.argparse.ArgumentDefaultsHelpFormatter)
1.  [function <span class="apidocSignatureSpan">argparse.</span>ArgumentDefaultsHelpFormatter (options)](#apidoc.element.argparse.ArgumentDefaultsHelpFormatter.ArgumentDefaultsHelpFormatter)
1.  [function <span class="apidocSignatureSpan">argparse.ArgumentDefaultsHelpFormatter.</span>super_ (options)](#apidoc.element.argparse.ArgumentDefaultsHelpFormatter.super_)

#### [module argparse.ArgumentDefaultsHelpFormatter.prototype](#apidoc.module.argparse.ArgumentDefaultsHelpFormatter.prototype)
1.  [function <span class="apidocSignatureSpan">argparse.ArgumentDefaultsHelpFormatter.prototype.</span>_getHelpString (action)](#apidoc.element.argparse.ArgumentDefaultsHelpFormatter.prototype._getHelpString)

#### [module argparse.ArgumentParser](#apidoc.module.argparse.ArgumentParser)
1.  [function <span class="apidocSignatureSpan">argparse.</span>ArgumentParser (options)](#apidoc.element.argparse.ArgumentParser.ArgumentParser)
1.  [function <span class="apidocSignatureSpan">argparse.ArgumentParser.</span>super_ (options)](#apidoc.element.argparse.ArgumentParser.super_)

#### [module argparse.ArgumentParser.prototype](#apidoc.module.argparse.ArgumentParser.prototype)
1.  [function <span class="apidocSignatureSpan">argparse.ArgumentParser.prototype.</span>_addAction (action)](#apidoc.element.argparse.ArgumentParser.prototype._addAction)
1.  [function <span class="apidocSignatureSpan">argparse.ArgumentParser.prototype.</span>_checkValue (action, value)](#apidoc.element.argparse.ArgumentParser.prototype._checkValue)
1.  [function <span class="apidocSignatureSpan">argparse.ArgumentParser.prototype.</span>_getFormatter ()](#apidoc.element.argparse.ArgumentParser.prototype._getFormatter)
1.  [function <span class="apidocSignatureSpan">argparse.ArgumentParser.prototype.</span>_getNargsPattern (action)](#apidoc.element.argparse.ArgumentParser.prototype._getNargsPattern)
1.  [function <span class="apidocSignatureSpan">argparse.ArgumentParser.prototype.</span>_getOptionTuples (optionString)](#apidoc.element.argparse.ArgumentParser.prototype._getOptionTuples)
1.  [function <span class="apidocSignatureSpan">argparse.ArgumentParser.prototype.</span>_getOptionalActions ()](#apidoc.element.argparse.ArgumentParser.prototype._getOptionalActions)
1.  [function <span class="apidocSignatureSpan">argparse.ArgumentParser.prototype.</span>_getPositionalActions ()](#apidoc.element.argparse.ArgumentParser.prototype._getPositionalActions)
1.  [function <span class="apidocSignatureSpan">argparse.ArgumentParser.prototype.</span>_getValue (action, argString)](#apidoc.element.argparse.ArgumentParser.prototype._getValue)
1.  [function <span class="apidocSignatureSpan">argparse.ArgumentParser.prototype.</span>_getValues (action, argStrings)](#apidoc.element.argparse.ArgumentParser.prototype._getValues)
1.  [function <span class="apidocSignatureSpan">argparse.ArgumentParser.prototype.</span>_matchArgument (action, regexpArgStrings)](#apidoc.element.argparse.ArgumentParser.prototype._matchArgument)
1.  [function <span class="apidocSignatureSpan">argparse.ArgumentParser.prototype.</span>_matchArgumentsPartial (actions, regexpArgStrings)](#apidoc.element.argparse.ArgumentParser.prototype._matchArgumentsPartial)
1.  [function <span class="apidocSignatureSpan">argparse.ArgumentParser.prototype.</span>_parseKnownArgs (argStrings, namespace)](#apidoc.element.argparse.ArgumentParser.prototype._parseKnownArgs)
1.  [function <span class="apidocSignatureSpan">argparse.ArgumentParser.prototype.</span>_parseOptional (argString)](#apidoc.element.argparse.ArgumentParser.prototype._parseOptional)
1.  [function <span class="apidocSignatureSpan">argparse.ArgumentParser.prototype.</span>_printMessage (message, stream)](#apidoc.element.argparse.ArgumentParser.prototype._printMessage)
1.  [function <span class="apidocSignatureSpan">argparse.ArgumentParser.prototype.</span>_readArgsFromFiles (argStrings)](#apidoc.element.argparse.ArgumentParser.prototype._readArgsFromFiles)
1.  [function <span class="apidocSignatureSpan">argparse.ArgumentParser.prototype.</span>addSubparsers (options)](#apidoc.element.argparse.ArgumentParser.prototype.addSubparsers)
1.  [function <span class="apidocSignatureSpan">argparse.ArgumentParser.prototype.</span>convertArgLineToArgs (argLine)](#apidoc.element.argparse.ArgumentParser.prototype.convertArgLineToArgs)
1.  [function <span class="apidocSignatureSpan">argparse.ArgumentParser.prototype.</span>error (err)](#apidoc.element.argparse.ArgumentParser.prototype.error)
1.  [function <span class="apidocSignatureSpan">argparse.ArgumentParser.prototype.</span>exit (status, message)](#apidoc.element.argparse.ArgumentParser.prototype.exit)
1.  [function <span class="apidocSignatureSpan">argparse.ArgumentParser.prototype.</span>formatHelp ()](#apidoc.element.argparse.ArgumentParser.prototype.formatHelp)
1.  [function <span class="apidocSignatureSpan">argparse.ArgumentParser.prototype.</span>formatUsage ()](#apidoc.element.argparse.ArgumentParser.prototype.formatUsage)
1.  [function <span class="apidocSignatureSpan">argparse.ArgumentParser.prototype.</span>parseArgs (args, namespace)](#apidoc.element.argparse.ArgumentParser.prototype.parseArgs)
1.  [function <span class="apidocSignatureSpan">argparse.ArgumentParser.prototype.</span>parseKnownArgs (args, namespace)](#apidoc.element.argparse.ArgumentParser.prototype.parseKnownArgs)
1.  [function <span class="apidocSignatureSpan">argparse.ArgumentParser.prototype.</span>printHelp ()](#apidoc.element.argparse.ArgumentParser.prototype.printHelp)
1.  [function <span class="apidocSignatureSpan">argparse.ArgumentParser.prototype.</span>printUsage ()](#apidoc.element.argparse.ArgumentParser.prototype.printUsage)

#### [module argparse.ArgumentParser.super_](#apidoc.module.argparse.ArgumentParser.super_)
1.  [function <span class="apidocSignatureSpan">argparse.ArgumentParser.</span>super_ (options)](#apidoc.element.argparse.ArgumentParser.super_.super_)

#### [module argparse.ArgumentParser.super_.prototype](#apidoc.module.argparse.ArgumentParser.super_.prototype)
1.  [function <span class="apidocSignatureSpan">argparse.ArgumentParser.super_.prototype.</span>_addAction (action)](#apidoc.element.argparse.ArgumentParser.super_.prototype._addAction)
1.  [function <span class="apidocSignatureSpan">argparse.ArgumentParser.super_.prototype.</span>_addContainerActions (container)](#apidoc.element.argparse.ArgumentParser.super_.prototype._addContainerActions)
1.  [function <span class="apidocSignatureSpan">argparse.ArgumentParser.super_.prototype.</span>_checkConflict (action)](#apidoc.element.argparse.ArgumentParser.super_.prototype._checkConflict)
1.  [function <span class="apidocSignatureSpan">argparse.ArgumentParser.super_.prototype.</span>_getHandler ()](#apidoc.element.argparse.ArgumentParser.super_.prototype._getHandler)
1.  [function <span class="apidocSignatureSpan">argparse.ArgumentParser.super_.prototype.</span>_getOptional (args, options)](#apidoc.element.argparse.ArgumentParser.super_.prototype._getOptional)
1.  [function <span class="apidocSignatureSpan">argparse.ArgumentParser.super_.prototype.</span>_getPositional (dest, options)](#apidoc.element.argparse.ArgumentParser.super_.prototype._getPositional)
1.  [function <span class="apidocSignatureSpan">argparse.ArgumentParser.super_.prototype.</span>_handleConflictError (action, conflOptionals)](#apidoc.element.argparse.ArgumentParser.super_.prototype._handleConflictError)
1.  [function <span class="apidocSignatureSpan">argparse.ArgumentParser.super_.prototype.</span>_handleConflictResolve (action, conflOptionals)](#apidoc.element.argparse.ArgumentParser.super_.prototype._handleConflictResolve)
1.  [function <span class="apidocSignatureSpan">argparse.ArgumentParser.super_.prototype.</span>_popActionClass (options, defaultValue)](#apidoc.element.argparse.ArgumentParser.super_.prototype._popActionClass)
1.  [function <span class="apidocSignatureSpan">argparse.ArgumentParser.super_.prototype.</span>_registryGet (registryName, value, defaultValue)](#apidoc.element.argparse.ArgumentParser.super_.prototype._registryGet)
1.  [function <span class="apidocSignatureSpan">argparse.ArgumentParser.super_.prototype.</span>_removeAction (action)](#apidoc.element.argparse.ArgumentParser.super_.prototype._removeAction)
1.  [function <span class="apidocSignatureSpan">argparse.ArgumentParser.super_.prototype.</span>addArgument (args, options)](#apidoc.element.argparse.ArgumentParser.super_.prototype.addArgument)
1.  [function <span class="apidocSignatureSpan">argparse.ArgumentParser.super_.prototype.</span>addArgumentGroup (options)](#apidoc.element.argparse.ArgumentParser.super_.prototype.addArgumentGroup)
1.  [function <span class="apidocSignatureSpan">argparse.ArgumentParser.super_.prototype.</span>addMutuallyExclusiveGroup (options)](#apidoc.element.argparse.ArgumentParser.super_.prototype.addMutuallyExclusiveGroup)
1.  [function <span class="apidocSignatureSpan">argparse.ArgumentParser.super_.prototype.</span>getDefault (dest)](#apidoc.element.argparse.ArgumentParser.super_.prototype.getDefault)
1.  [function <span class="apidocSignatureSpan">argparse.ArgumentParser.super_.prototype.</span>register (registryName, value, object)](#apidoc.element.argparse.ArgumentParser.super_.prototype.register)
1.  [function <span class="apidocSignatureSpan">argparse.ArgumentParser.super_.prototype.</span>setDefaults (options)](#apidoc.element.argparse.ArgumentParser.super_.prototype.setDefaults)

#### [module argparse.HelpFormatter](#apidoc.module.argparse.HelpFormatter)
1.  [function <span class="apidocSignatureSpan">argparse.</span>HelpFormatter (options)](#apidoc.element.argparse.HelpFormatter.HelpFormatter)

#### [module argparse.HelpFormatter.prototype](#apidoc.module.argparse.HelpFormatter.prototype)
1.  [function <span class="apidocSignatureSpan">argparse.HelpFormatter.prototype.</span>_addItem (func, args)](#apidoc.element.argparse.HelpFormatter.prototype._addItem)
1.  [function <span class="apidocSignatureSpan">argparse.HelpFormatter.prototype.</span>_dedent ()](#apidoc.element.argparse.HelpFormatter.prototype._dedent)
1.  [function <span class="apidocSignatureSpan">argparse.HelpFormatter.prototype.</span>_expandHelp (action)](#apidoc.element.argparse.HelpFormatter.prototype._expandHelp)
1.  [function <span class="apidocSignatureSpan">argparse.HelpFormatter.prototype.</span>_fillText (text, width, indent)](#apidoc.element.argparse.HelpFormatter.prototype._fillText)
1.  [function <span class="apidocSignatureSpan">argparse.HelpFormatter.prototype.</span>_formatAction (action)](#apidoc.element.argparse.HelpFormatter.prototype._formatAction)
1.  [function <span class="apidocSignatureSpan">argparse.HelpFormatter.prototype.</span>_formatActionInvocation (action)](#apidoc.element.argparse.HelpFormatter.prototype._formatActionInvocation)
1.  [function <span class="apidocSignatureSpan">argparse.HelpFormatter.prototype.</span>_formatActionsUsage (actions, groups)](#apidoc.element.argparse.HelpFormatter.prototype._formatActionsUsage)
1.  [function <span class="apidocSignatureSpan">argparse.HelpFormatter.prototype.</span>_formatArgs (action, metavarDefault)](#apidoc.element.argparse.HelpFormatter.prototype._formatArgs)
1.  [function <span class="apidocSignatureSpan">argparse.HelpFormatter.prototype.</span>_formatText (text)](#apidoc.element.argparse.HelpFormatter.prototype._formatText)
1.  [function <span class="apidocSignatureSpan">argparse.HelpFormatter.prototype.</span>_formatUsage (usage, actions, groups, prefix)](#apidoc.element.argparse.HelpFormatter.prototype._formatUsage)
1.  [function <span class="apidocSignatureSpan">argparse.HelpFormatter.prototype.</span>_getHelpString (action)](#apidoc.element.argparse.HelpFormatter.prototype._getHelpString)
1.  [function <span class="apidocSignatureSpan">argparse.HelpFormatter.prototype.</span>_indent ()](#apidoc.element.argparse.HelpFormatter.prototype._indent)
1.  [function <span class="apidocSignatureSpan">argparse.HelpFormatter.prototype.</span>_joinParts (partStrings)](#apidoc.element.argparse.HelpFormatter.prototype._joinParts)
1.  [function <span class="apidocSignatureSpan">argparse.HelpFormatter.prototype.</span>_metavarFormatter (action, metavarDefault)](#apidoc.element.argparse.HelpFormatter.prototype._metavarFormatter)
1.  [function <span class="apidocSignatureSpan">argparse.HelpFormatter.prototype.</span>_splitLines (text, width)](#apidoc.element.argparse.HelpFormatter.prototype._splitLines)
1.  [function <span class="apidocSignatureSpan">argparse.HelpFormatter.prototype.</span>addArgument (action)](#apidoc.element.argparse.HelpFormatter.prototype.addArgument)
1.  [function <span class="apidocSignatureSpan">argparse.HelpFormatter.prototype.</span>addArguments (actions)](#apidoc.element.argparse.HelpFormatter.prototype.addArguments)
1.  [function <span class="apidocSignatureSpan">argparse.HelpFormatter.prototype.</span>addText (text)](#apidoc.element.argparse.HelpFormatter.prototype.addText)
1.  [function <span class="apidocSignatureSpan">argparse.HelpFormatter.prototype.</span>addUsage (usage, actions, groups, prefix)](#apidoc.element.argparse.HelpFormatter.prototype.addUsage)
1.  [function <span class="apidocSignatureSpan">argparse.HelpFormatter.prototype.</span>endSection ()](#apidoc.element.argparse.HelpFormatter.prototype.endSection)
1.  [function <span class="apidocSignatureSpan">argparse.HelpFormatter.prototype.</span>formatHelp ()](#apidoc.element.argparse.HelpFormatter.prototype.formatHelp)
1.  [function <span class="apidocSignatureSpan">argparse.HelpFormatter.prototype.</span>startSection (heading)](#apidoc.element.argparse.HelpFormatter.prototype.startSection)

#### [module argparse.Namespace](#apidoc.module.argparse.Namespace)
1.  [function <span class="apidocSignatureSpan">argparse.</span>Namespace (options)](#apidoc.element.argparse.Namespace.Namespace)

#### [module argparse.Namespace.prototype](#apidoc.module.argparse.Namespace.prototype)
1.  [function <span class="apidocSignatureSpan">argparse.Namespace.prototype.</span>get (key, defaultValue)](#apidoc.element.argparse.Namespace.prototype.get)
1.  [function <span class="apidocSignatureSpan">argparse.Namespace.prototype.</span>isset (key)](#apidoc.element.argparse.Namespace.prototype.isset)
1.  [function <span class="apidocSignatureSpan">argparse.Namespace.prototype.</span>set (key, value)](#apidoc.element.argparse.Namespace.prototype.set)
1.  [function <span class="apidocSignatureSpan">argparse.Namespace.prototype.</span>unset (key, defaultValue)](#apidoc.element.argparse.Namespace.prototype.unset)

#### [module argparse.RawDescriptionHelpFormatter](#apidoc.module.argparse.RawDescriptionHelpFormatter)
1.  [function <span class="apidocSignatureSpan">argparse.</span>RawDescriptionHelpFormatter (options)](#apidoc.element.argparse.RawDescriptionHelpFormatter.RawDescriptionHelpFormatter)
1.  [function <span class="apidocSignatureSpan">argparse.RawDescriptionHelpFormatter.</span>super_ (options)](#apidoc.element.argparse.RawDescriptionHelpFormatter.super_)

#### [module argparse.RawDescriptionHelpFormatter.prototype](#apidoc.module.argparse.RawDescriptionHelpFormatter.prototype)
1.  [function <span class="apidocSignatureSpan">argparse.RawDescriptionHelpFormatter.prototype.</span>_fillText (text, width, indent)](#apidoc.element.argparse.RawDescriptionHelpFormatter.prototype._fillText)

#### [module argparse.RawTextHelpFormatter](#apidoc.module.argparse.RawTextHelpFormatter)
1.  [function <span class="apidocSignatureSpan">argparse.</span>RawTextHelpFormatter (options)](#apidoc.element.argparse.RawTextHelpFormatter.RawTextHelpFormatter)
1.  [function <span class="apidocSignatureSpan">argparse.RawTextHelpFormatter.</span>super_ (options)](#apidoc.element.argparse.RawTextHelpFormatter.super_)

#### [module argparse.RawTextHelpFormatter.prototype](#apidoc.module.argparse.RawTextHelpFormatter.prototype)
1.  [function <span class="apidocSignatureSpan">argparse.RawTextHelpFormatter.prototype.</span>_splitLines (text)](#apidoc.element.argparse.RawTextHelpFormatter.prototype._splitLines)

#### [module argparse.utils](#apidoc.module.argparse.utils)
1.  [function <span class="apidocSignatureSpan">argparse.utils.</span>arrayEqual (a, b)](#apidoc.element.argparse.utils.arrayEqual)
1.  [function <span class="apidocSignatureSpan">argparse.utils.</span>arrayUnion ()](#apidoc.element.argparse.utils.arrayUnion)
1.  [function <span class="apidocSignatureSpan">argparse.utils.</span>capitalize (str)](#apidoc.element.argparse.utils.capitalize)
1.  [function <span class="apidocSignatureSpan">argparse.utils.</span>extend (dest, src)](#apidoc.element.argparse.utils.extend)
1.  [function <span class="apidocSignatureSpan">argparse.utils.</span>has (obj, key)](#apidoc.element.argparse.utils.has)
1.  [function <span class="apidocSignatureSpan">argparse.utils.</span>repeat (str, num)](#apidoc.element.argparse.utils.repeat)
1.  [function <span class="apidocSignatureSpan">argparse.utils.</span>trimChars (str, chars)](#apidoc.element.argparse.utils.trimChars)
1.  [function <span class="apidocSignatureSpan">argparse.utils.</span>trimEnd (str)](#apidoc.element.argparse.utils.trimEnd)



# <a name="apidoc.module.argparse"></a>[module argparse](#apidoc.module.argparse)

#### <a name="apidoc.element.argparse.Action"></a>[function <span class="apidocSignatureSpan">argparse.</span>Action (options)](#apidoc.element.argparse.Action)
- description and source-code
```javascript
function Action(options) {
  options = options || {};
  this.optionStrings = options.optionStrings || [];
  this.dest = options.dest;
  this.nargs = typeof options.nargs !== 'undefined' ? options.nargs : null;
  this.constant = typeof options.constant !== 'undefined' ? options.constant : null;
  this.defaultValue = options.defaultValue;
  this.type = typeof options.type !== 'undefined' ? options.type : null;
  this.choices = typeof options.choices !== 'undefined' ? options.choices : null;
  this.required = typeof options.required !== 'undefined' ? options.required : false;
  this.help = typeof options.help !== 'undefined' ? options.help : null;
  this.metavar = typeof options.metavar !== 'undefined' ? options.metavar : null;

  if (!(this.optionStrings instanceof Array)) {
    throw new Error('optionStrings should be an array');
  }
  if (typeof this.required !== 'undefined' && typeof this.required !== 'boolean') {
    throw new Error('required should be a boolean');
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.ArgumentDefaultsHelpFormatter"></a>[function <span class="apidocSignatureSpan">argparse.</span>ArgumentDefaultsHelpFormatter (options)](#apidoc.element.argparse.ArgumentDefaultsHelpFormatter)
- description and source-code
```javascript
function ArgumentDefaultsHelpFormatter(options) {
  HelpFormatter.call(this, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.ArgumentParser"></a>[function <span class="apidocSignatureSpan">argparse.</span>ArgumentParser (options)](#apidoc.element.argparse.ArgumentParser)
- description and source-code
```javascript
function ArgumentParser(options) {
  if (!(this instanceof ArgumentParser)) {
    return new ArgumentParser(options);
  }
  var self = this;
  options = options || {};

  options.description = (options.description || null);
  options.argumentDefault = (options.argumentDefault || null);
  options.prefixChars = (options.prefixChars || '-');
  options.conflictHandler = (options.conflictHandler || 'error');
  ActionContainer.call(this, options);

  options.addHelp = typeof options.addHelp === 'undefined' || !!options.addHelp;
  options.parents = options.parents || [];
  // default program name
  options.prog = (options.prog || Path.basename(process.argv[1]));
  this.prog = options.prog;
  this.usage = options.usage;
  this.epilog = options.epilog;
  this.version = options.version;

  this.debug = (options.debug === true);

  this.formatterClass = (options.formatterClass || HelpFormatter);
  this.fromfilePrefixChars = options.fromfilePrefixChars || null;
  this._positionals = this.addArgumentGroup({ title: 'Positional arguments' });
  this._optionals = this.addArgumentGroup({ title: 'Optional arguments' });
  this._subparsers = null;

  // register types
  function FUNCTION_IDENTITY(o) {
    return o;
  }
  this.register('type', 'auto', FUNCTION_IDENTITY);
  this.register('type', null, FUNCTION_IDENTITY);
  this.register('type', 'int', function (x) {
    var result = parseInt(x, 10);
    if (isNaN(result)) {
      throw new Error(x + ' is not a valid integer.');
    }
    return result;
  });
  this.register('type', 'float', function (x) {
    var result = parseFloat(x);
    if (isNaN(result)) {
      throw new Error(x + ' is not a valid float.');
    }
    return result;
  });
  this.register('type', 'string', function (x) {
    return '' + x;
  });

  // add help and version arguments if necessary
  var defaultPrefix = (this.prefixChars.indexOf('-') > -1) ? '-' : this.prefixChars[0];
  if (options.addHelp) {
    this.addArgument(
      [ defaultPrefix + 'h', defaultPrefix + defaultPrefix + 'help' ],
      {
        action: 'help',
        defaultValue: c.SUPPRESS,
        help: 'Show this help message and exit.'
      }
    );
  }
  if (typeof this.version !== 'undefined') {
    this.addArgument(
      [ defaultPrefix + 'v', defaultPrefix + defaultPrefix + 'version' ],
      {
        action: 'version',
        version: this.version,
        defaultValue: c.SUPPRESS,
        help: "Show program's version number and exit."
      }
    );
  }

  // add parent arguments and defaults
  options.parents.forEach(function (parent) {
    self._addContainerActions(parent);
    if (typeof parent._defaults !== 'undefined') {
      for (var defaultKey in parent._defaults) {
        if (parent._defaults.hasOwnProperty(defaultKey)) {
          self._defaults[defaultKey] = parent._defaults[defaultKey];
        }
      }
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.ArgumentParser.super_"></a>[function <span class="apidocSignatureSpan">argparse.</span>ArgumentParser.super_ (options)](#apidoc.element.argparse.ArgumentParser.super_)
- description and source-code
```javascript
function ActionContainer(options) {
  options = options || {};

  this.description = options.description;
  this.argumentDefault = options.argumentDefault;
  this.prefixChars = options.prefixChars || '';
  this.conflictHandler = options.conflictHandler;

  // set up registries
  this._registries = {};

  // register actions
  this.register('action', null, ActionStore);
  this.register('action', 'store', ActionStore);
  this.register('action', 'storeConst', ActionStoreConstant);
  this.register('action', 'storeTrue', ActionStoreTrue);
  this.register('action', 'storeFalse', ActionStoreFalse);
  this.register('action', 'append', ActionAppend);
  this.register('action', 'appendConst', ActionAppendConstant);
  this.register('action', 'count', ActionCount);
  this.register('action', 'help', ActionHelp);
  this.register('action', 'version', ActionVersion);
  this.register('action', 'parsers', ActionSubparsers);

  // raise an exception if the conflict handler is invalid
  this._getHandler();

  // action storage
  this._actions = [];
  this._optionStringActions = {};

  // groups
  this._actionGroups = [];
  this._mutuallyExclusiveGroups = [];

  // defaults storage
  this._defaults = {};

  // determines whether an "option" looks like a negative number
  // -1, -1.5 -5e+4
  this._regexpNegativeNumber = new RegExp('^[-]?[0-9]*\\.?[0-9]+([eE][-+]?[0-9]+)?$');

  // whether or not there are any optionals that look like negative
  // numbers -- uses a list so it can be shared and edited
  this._hasNegativeNumberOptionals = [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.HelpFormatter"></a>[function <span class="apidocSignatureSpan">argparse.</span>HelpFormatter (options)](#apidoc.element.argparse.HelpFormatter)
- description and source-code
```javascript
function HelpFormatter(options) {
  options = options || {};

  this._prog = options.prog;

  this._maxHelpPosition = options.maxHelpPosition || 24;
  this._width = (options.width || ((process.env.COLUMNS || 80) - 2));

  this._currentIndent = 0;
  this._indentIncriment = options.indentIncriment || 2;
  this._level = 0;
  this._actionMaxLength = 0;

  this._rootSection = new Section(null);
  this._currentSection = this._rootSection;

  this._whitespaceMatcher = new RegExp('\\s+', 'g');
  this._longBreakMatcher = new RegExp(c.EOL + c.EOL + c.EOL + '+', 'g');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.Namespace"></a>[function <span class="apidocSignatureSpan">argparse.</span>Namespace (options)](#apidoc.element.argparse.Namespace)
- description and source-code
```javascript
function Namespace(options) {
  $$.extend(this, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.RawDescriptionHelpFormatter"></a>[function <span class="apidocSignatureSpan">argparse.</span>RawDescriptionHelpFormatter (options)](#apidoc.element.argparse.RawDescriptionHelpFormatter)
- description and source-code
```javascript
function RawDescriptionHelpFormatter(options) {
  HelpFormatter.call(this, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.RawTextHelpFormatter"></a>[function <span class="apidocSignatureSpan">argparse.</span>RawTextHelpFormatter (options)](#apidoc.element.argparse.RawTextHelpFormatter)
- description and source-code
```javascript
function RawTextHelpFormatter(options) {
  RawDescriptionHelpFormatter.call(this, options);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.argparse.Action"></a>[module argparse.Action](#apidoc.module.argparse.Action)

#### <a name="apidoc.element.argparse.Action.Action"></a>[function <span class="apidocSignatureSpan">argparse.</span>Action (options)](#apidoc.element.argparse.Action.Action)
- description and source-code
```javascript
function Action(options) {
  options = options || {};
  this.optionStrings = options.optionStrings || [];
  this.dest = options.dest;
  this.nargs = typeof options.nargs !== 'undefined' ? options.nargs : null;
  this.constant = typeof options.constant !== 'undefined' ? options.constant : null;
  this.defaultValue = options.defaultValue;
  this.type = typeof options.type !== 'undefined' ? options.type : null;
  this.choices = typeof options.choices !== 'undefined' ? options.choices : null;
  this.required = typeof options.required !== 'undefined' ? options.required : false;
  this.help = typeof options.help !== 'undefined' ? options.help : null;
  this.metavar = typeof options.metavar !== 'undefined' ? options.metavar : null;

  if (!(this.optionStrings instanceof Array)) {
    throw new Error('optionStrings should be an array');
  }
  if (typeof this.required !== 'undefined' && typeof this.required !== 'boolean') {
    throw new Error('required should be a boolean');
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.argparse.Action.prototype"></a>[module argparse.Action.prototype](#apidoc.module.argparse.Action.prototype)

#### <a name="apidoc.element.argparse.Action.prototype.call"></a>[function <span class="apidocSignatureSpan">argparse.Action.prototype.</span>call ()](#apidoc.element.argparse.Action.prototype.call)
- description and source-code
```javascript
call = function () {
  throw new Error('.call() not defined');// Not Implemented error
}
```
- example usage
```shell
...
    }
  }
}
return result;
};

function has(obj, key) {
return Object.prototype.hasOwnProperty.call(obj, key);
}

exports.has = has;

exports.extend = function (dest, src) {
for (var i in src) {
  if (has(src, i)) { dest[i] = src[i]; }
...
```

#### <a name="apidoc.element.argparse.Action.prototype.getName"></a>[function <span class="apidocSignatureSpan">argparse.Action.prototype.</span>getName ()](#apidoc.element.argparse.Action.prototype.getName)
- description and source-code
```javascript
getName = function () {
  if (this.optionStrings.length > 0) {
    return this.optionStrings.join('/');
  } else if (this.metavar !== null && this.metavar !== c.SUPPRESS) {
    return this.metavar;
  } else if (typeof this.dest !== 'undefined' && this.dest !== c.SUPPRESS) {
    return this.dest;
  }
  return null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.Action.prototype.isOptional"></a>[function <span class="apidocSignatureSpan">argparse.Action.prototype.</span>isOptional ()](#apidoc.element.argparse.Action.prototype.isOptional)
- description and source-code
```javascript
isOptional = function () {
  return !this.isPositional();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.Action.prototype.isPositional"></a>[function <span class="apidocSignatureSpan">argparse.Action.prototype.</span>isPositional ()](#apidoc.element.argparse.Action.prototype.isPositional)
- description and source-code
```javascript
isPositional = function () {
  return (this.optionStrings.length === 0);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.argparse.ArgumentDefaultsHelpFormatter"></a>[module argparse.ArgumentDefaultsHelpFormatter](#apidoc.module.argparse.ArgumentDefaultsHelpFormatter)

#### <a name="apidoc.element.argparse.ArgumentDefaultsHelpFormatter.ArgumentDefaultsHelpFormatter"></a>[function <span class="apidocSignatureSpan">argparse.</span>ArgumentDefaultsHelpFormatter (options)](#apidoc.element.argparse.ArgumentDefaultsHelpFormatter.ArgumentDefaultsHelpFormatter)
- description and source-code
```javascript
function ArgumentDefaultsHelpFormatter(options) {
  HelpFormatter.call(this, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.ArgumentDefaultsHelpFormatter.super_"></a>[function <span class="apidocSignatureSpan">argparse.ArgumentDefaultsHelpFormatter.</span>super_ (options)](#apidoc.element.argparse.ArgumentDefaultsHelpFormatter.super_)
- description and source-code
```javascript
function HelpFormatter(options) {
  options = options || {};

  this._prog = options.prog;

  this._maxHelpPosition = options.maxHelpPosition || 24;
  this._width = (options.width || ((process.env.COLUMNS || 80) - 2));

  this._currentIndent = 0;
  this._indentIncriment = options.indentIncriment || 2;
  this._level = 0;
  this._actionMaxLength = 0;

  this._rootSection = new Section(null);
  this._currentSection = this._rootSection;

  this._whitespaceMatcher = new RegExp('\\s+', 'g');
  this._longBreakMatcher = new RegExp(c.EOL + c.EOL + c.EOL + '+', 'g');
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.argparse.ArgumentDefaultsHelpFormatter.prototype"></a>[module argparse.ArgumentDefaultsHelpFormatter.prototype](#apidoc.module.argparse.ArgumentDefaultsHelpFormatter.prototype)

#### <a name="apidoc.element.argparse.ArgumentDefaultsHelpFormatter.prototype._getHelpString"></a>[function <span class="apidocSignatureSpan">argparse.ArgumentDefaultsHelpFormatter.prototype.</span>_getHelpString (action)](#apidoc.element.argparse.ArgumentDefaultsHelpFormatter.prototype._getHelpString)
- description and source-code
```javascript
_getHelpString = function (action) {
  var help = action.help;
  if (action.help.indexOf('%(defaultValue)s') === -1) {
    if (action.defaultValue !== c.SUPPRESS) {
      var defaulting_nargs = [ c.OPTIONAL, c.ZERO_OR_MORE ];
      if (action.isOptional() || (defaulting_nargs.indexOf(action.nargs) >= 0)) {
        help += ' (default: %(defaultValue)s)';
      }
    }
  }
  return help;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.argparse.ArgumentParser"></a>[module argparse.ArgumentParser](#apidoc.module.argparse.ArgumentParser)

#### <a name="apidoc.element.argparse.ArgumentParser.ArgumentParser"></a>[function <span class="apidocSignatureSpan">argparse.</span>ArgumentParser (options)](#apidoc.element.argparse.ArgumentParser.ArgumentParser)
- description and source-code
```javascript
function ArgumentParser(options) {
  if (!(this instanceof ArgumentParser)) {
    return new ArgumentParser(options);
  }
  var self = this;
  options = options || {};

  options.description = (options.description || null);
  options.argumentDefault = (options.argumentDefault || null);
  options.prefixChars = (options.prefixChars || '-');
  options.conflictHandler = (options.conflictHandler || 'error');
  ActionContainer.call(this, options);

  options.addHelp = typeof options.addHelp === 'undefined' || !!options.addHelp;
  options.parents = options.parents || [];
  // default program name
  options.prog = (options.prog || Path.basename(process.argv[1]));
  this.prog = options.prog;
  this.usage = options.usage;
  this.epilog = options.epilog;
  this.version = options.version;

  this.debug = (options.debug === true);

  this.formatterClass = (options.formatterClass || HelpFormatter);
  this.fromfilePrefixChars = options.fromfilePrefixChars || null;
  this._positionals = this.addArgumentGroup({ title: 'Positional arguments' });
  this._optionals = this.addArgumentGroup({ title: 'Optional arguments' });
  this._subparsers = null;

  // register types
  function FUNCTION_IDENTITY(o) {
    return o;
  }
  this.register('type', 'auto', FUNCTION_IDENTITY);
  this.register('type', null, FUNCTION_IDENTITY);
  this.register('type', 'int', function (x) {
    var result = parseInt(x, 10);
    if (isNaN(result)) {
      throw new Error(x + ' is not a valid integer.');
    }
    return result;
  });
  this.register('type', 'float', function (x) {
    var result = parseFloat(x);
    if (isNaN(result)) {
      throw new Error(x + ' is not a valid float.');
    }
    return result;
  });
  this.register('type', 'string', function (x) {
    return '' + x;
  });

  // add help and version arguments if necessary
  var defaultPrefix = (this.prefixChars.indexOf('-') > -1) ? '-' : this.prefixChars[0];
  if (options.addHelp) {
    this.addArgument(
      [ defaultPrefix + 'h', defaultPrefix + defaultPrefix + 'help' ],
      {
        action: 'help',
        defaultValue: c.SUPPRESS,
        help: 'Show this help message and exit.'
      }
    );
  }
  if (typeof this.version !== 'undefined') {
    this.addArgument(
      [ defaultPrefix + 'v', defaultPrefix + defaultPrefix + 'version' ],
      {
        action: 'version',
        version: this.version,
        defaultValue: c.SUPPRESS,
        help: "Show program's version number and exit."
      }
    );
  }

  // add parent arguments and defaults
  options.parents.forEach(function (parent) {
    self._addContainerActions(parent);
    if (typeof parent._defaults !== 'undefined') {
      for (var defaultKey in parent._defaults) {
        if (parent._defaults.hasOwnProperty(defaultKey)) {
          self._defaults[defaultKey] = parent._defaults[defaultKey];
        }
      }
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.ArgumentParser.super_"></a>[function <span class="apidocSignatureSpan">argparse.ArgumentParser.</span>super_ (options)](#apidoc.element.argparse.ArgumentParser.super_)
- description and source-code
```javascript
function ActionContainer(options) {
  options = options || {};

  this.description = options.description;
  this.argumentDefault = options.argumentDefault;
  this.prefixChars = options.prefixChars || '';
  this.conflictHandler = options.conflictHandler;

  // set up registries
  this._registries = {};

  // register actions
  this.register('action', null, ActionStore);
  this.register('action', 'store', ActionStore);
  this.register('action', 'storeConst', ActionStoreConstant);
  this.register('action', 'storeTrue', ActionStoreTrue);
  this.register('action', 'storeFalse', ActionStoreFalse);
  this.register('action', 'append', ActionAppend);
  this.register('action', 'appendConst', ActionAppendConstant);
  this.register('action', 'count', ActionCount);
  this.register('action', 'help', ActionHelp);
  this.register('action', 'version', ActionVersion);
  this.register('action', 'parsers', ActionSubparsers);

  // raise an exception if the conflict handler is invalid
  this._getHandler();

  // action storage
  this._actions = [];
  this._optionStringActions = {};

  // groups
  this._actionGroups = [];
  this._mutuallyExclusiveGroups = [];

  // defaults storage
  this._defaults = {};

  // determines whether an "option" looks like a negative number
  // -1, -1.5 -5e+4
  this._regexpNegativeNumber = new RegExp('^[-]?[0-9]*\\.?[0-9]+([eE][-+]?[0-9]+)?$');

  // whether or not there are any optionals that look like negative
  // numbers -- uses a list so it can be shared and edited
  this._hasNegativeNumberOptionals = [];
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.argparse.ArgumentParser.prototype"></a>[module argparse.ArgumentParser.prototype](#apidoc.module.argparse.ArgumentParser.prototype)

#### <a name="apidoc.element.argparse.ArgumentParser.prototype._addAction"></a>[function <span class="apidocSignatureSpan">argparse.ArgumentParser.prototype.</span>_addAction (action)](#apidoc.element.argparse.ArgumentParser.prototype._addAction)
- description and source-code
```javascript
_addAction = function (action) {
  if (action.isOptional()) {
    this._optionals._addAction(action);
  } else {
    this._positionals._addAction(action);
  }
  return action;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.ArgumentParser.prototype._checkValue"></a>[function <span class="apidocSignatureSpan">argparse.ArgumentParser.prototype.</span>_checkValue (action, value)](#apidoc.element.argparse.ArgumentParser.prototype._checkValue)
- description and source-code
```javascript
_checkValue = function (action, value) {
  // converted value must be one of the choices (if specified)
  var choices = action.choices;
  if (choices) {
    // choise for argument can by array or string
    if ((typeof choices === 'string' || Array.isArray(choices)) &&
        choices.indexOf(value) !== -1) {
      return;
    }
    // choise for subparsers can by only hash
    if (typeof choices === 'object' && !Array.isArray(choices) && choices[value]) {
      return;
    }

    if (typeof choices === 'string') {
      choices = choices.split('').join(', ');
    } else if (Array.isArray(choices)) {
      choices =  choices.join(', ');
    } else {
      choices =  Object.keys(choices).join(', ');
    }
    var message = format('Invalid choice: %s (choose from [%s])', value, choices);
    throw argumentErrorHelper(action, message);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.ArgumentParser.prototype._getFormatter"></a>[function <span class="apidocSignatureSpan">argparse.ArgumentParser.prototype.</span>_getFormatter ()](#apidoc.element.argparse.ArgumentParser.prototype._getFormatter)
- description and source-code
```javascript
_getFormatter = function () {
  var FormatterClass = this.formatterClass;
  var formatter = new FormatterClass({ prog: this.prog });
  return formatter;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.ArgumentParser.prototype._getNargsPattern"></a>[function <span class="apidocSignatureSpan">argparse.ArgumentParser.prototype.</span>_getNargsPattern (action)](#apidoc.element.argparse.ArgumentParser.prototype._getNargsPattern)
- description and source-code
```javascript
_getNargsPattern = function (action) {
  // in all examples below, we have to allow for '--' args
  // which are represented as '-' in the pattern
  var regexpNargs;

  switch (action.nargs) {
    // the default (null) is assumed to be a single argument
    case undefined:
    case null:
      regexpNargs = '(-*A-*)';
      break;
    // allow zero or more arguments
    case c.OPTIONAL:
      regexpNargs = '(-*A?-*)';
      break;
    // allow zero or more arguments
    case c.ZERO_OR_MORE:
      regexpNargs = '(-*[A-]*)';
      break;
    // allow one or more arguments
    case c.ONE_OR_MORE:
      regexpNargs = '(-*A[A-]*)';
      break;
    // allow any number of options or arguments
    case c.REMAINDER:
      regexpNargs = '([-AO]*)';
      break;
    // allow one argument followed by any number of options or arguments
    case c.PARSER:
      regexpNargs = '(-*A[-AO]*)';
      break;
    // all others should be integers
    default:
      regexpNargs = '(-*' + $$.repeat('-*A', action.nargs) + '-*)';
  }

  // if this is an optional action, -- is not allowed
  if (action.isOptional()) {
    regexpNargs = regexpNargs.replace(/-\*/g, '');
    regexpNargs = regexpNargs.replace(/-/g, '');
  }

  // return the pattern
  return regexpNargs;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.ArgumentParser.prototype._getOptionTuples"></a>[function <span class="apidocSignatureSpan">argparse.ArgumentParser.prototype.</span>_getOptionTuples (optionString)](#apidoc.element.argparse.ArgumentParser.prototype._getOptionTuples)
- description and source-code
```javascript
_getOptionTuples = function (optionString) {
  var result = [];
  var chars = this.prefixChars;
  var optionPrefix;
  var argExplicit;
  var action;
  var actionOptionString;

  // option strings starting with two prefix characters are only split at
  // the '='
  if (chars.indexOf(optionString[0]) >= 0 && chars.indexOf(optionString[1]) >= 0) {
    if (optionString.indexOf('=') >= 0) {
      var optionStringSplit = optionString.split('=', 1);

      optionPrefix = optionStringSplit[0];
      argExplicit = optionStringSplit[1];
    } else {
      optionPrefix = optionString;
      argExplicit = null;
    }

    for (actionOptionString in this._optionStringActions) {
      if (actionOptionString.substr(0, optionPrefix.length) === optionPrefix) {
        action = this._optionStringActions[actionOptionString];
        result.push([ action, actionOptionString, argExplicit ]);
      }
    }

  // single character options can be concatenated with their arguments
  // but multiple character options always have to have their argument
  // separate
  } else if (chars.indexOf(optionString[0]) >= 0 && chars.indexOf(optionString[1]) < 0) {
    optionPrefix = optionString;
    argExplicit = null;
    var optionPrefixShort = optionString.substr(0, 2);
    var argExplicitShort = optionString.substr(2);

    for (actionOptionString in this._optionStringActions) {
      if (!$$.has(this._optionStringActions, actionOptionString)) continue;

      action = this._optionStringActions[actionOptionString];
      if (actionOptionString === optionPrefixShort) {
        result.push([ action, actionOptionString, argExplicitShort ]);
      } else if (actionOptionString.substr(0, optionPrefix.length) === optionPrefix) {
        result.push([ action, actionOptionString, argExplicit ]);
      }
    }

  // shouldn't ever get here
  } else {
    throw new Error(format('Unexpected option string: %s.', optionString));
  }
  // return the collected option tuples
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.ArgumentParser.prototype._getOptionalActions"></a>[function <span class="apidocSignatureSpan">argparse.ArgumentParser.prototype.</span>_getOptionalActions ()](#apidoc.element.argparse.ArgumentParser.prototype._getOptionalActions)
- description and source-code
```javascript
_getOptionalActions = function () {
  return this._actions.filter(function (action) {
    return action.isOptional();
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.ArgumentParser.prototype._getPositionalActions"></a>[function <span class="apidocSignatureSpan">argparse.ArgumentParser.prototype.</span>_getPositionalActions ()](#apidoc.element.argparse.ArgumentParser.prototype._getPositionalActions)
- description and source-code
```javascript
_getPositionalActions = function () {
  return this._actions.filter(function (action) {
    return action.isPositional();
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.ArgumentParser.prototype._getValue"></a>[function <span class="apidocSignatureSpan">argparse.ArgumentParser.prototype.</span>_getValue (action, argString)](#apidoc.element.argparse.ArgumentParser.prototype._getValue)
- description and source-code
```javascript
_getValue = function (action, argString) {
  var result;

  var typeFunction = this._registryGet('type', action.type, action.type);
  if (typeof typeFunction !== 'function') {
    var message = format('%s is not callable', typeFunction);
    throw argumentErrorHelper(action, message);
  }

  // convert the value to the appropriate type
  try {
    result = typeFunction(argString);

    // ArgumentTypeErrors indicate errors
    // If action.type is not a registered string, it is a function
    // Try to deduce its name for inclusion in the error message
    // Failing that, include the error message it raised.
  } catch (e) {
    var name = null;
    if (typeof action.type === 'string') {
      name = action.type;
    } else {
      name = action.type.name || action.type.displayName || '<function>';
    }
    var msg = format('Invalid %s value: %s', name, argString);
    if (name === '<function>') { msg += '\n' + e.message; }
    throw argumentErrorHelper(action, msg);
  }
  // return the converted value
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.ArgumentParser.prototype._getValues"></a>[function <span class="apidocSignatureSpan">argparse.ArgumentParser.prototype.</span>_getValues (action, argStrings)](#apidoc.element.argparse.ArgumentParser.prototype._getValues)
- description and source-code
```javascript
_getValues = function (action, argStrings) {
  var self = this;

  // for everything but PARSER args, strip out '--'
  if (action.nargs !== c.PARSER && action.nargs !== c.REMAINDER) {
    argStrings = argStrings.filter(function (arrayElement) {
      return arrayElement !== '--';
    });
  }

  var value, argString;

  // optional argument produces a default when not present
  if (argStrings.length === 0 && action.nargs === c.OPTIONAL) {

    value = (action.isOptional()) ? action.constant : action.defaultValue;

    if (typeof (value) === 'string') {
      value = this._getValue(action, value);
      this._checkValue(action, value);
    }

  // when nargs='*' on a positional, if there were no command-line
  // args, use the default if it is anything other than None
  } else if (argStrings.length === 0 && action.nargs === c.ZERO_OR_MORE &&
    action.optionStrings.length === 0) {

    value = (action.defaultValue || argStrings);
    this._checkValue(action, value);

  // single argument or optional argument produces a single value
  } else if (argStrings.length === 1 &&
        (!action.nargs || action.nargs === c.OPTIONAL)) {

    argString = argStrings[0];
    value = this._getValue(action, argString);
    this._checkValue(action, value);

  // REMAINDER arguments convert all values, checking none
  } else if (action.nargs === c.REMAINDER) {
    value = argStrings.map(function (v) {
      return self._getValue(action, v);
    });

  // PARSER arguments convert all values, but check only the first
  } else if (action.nargs === c.PARSER) {
    value = argStrings.map(function (v) {
      return self._getValue(action, v);
    });
    this._checkValue(action, value[0]);

  // all other types of nargs produce a list
  } else {
    value = argStrings.map(function (v) {
      return self._getValue(action, v);
    });
    value.forEach(function (v) {
      self._checkValue(action, v);
    });
  }

  // return the converted value
  return value;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.ArgumentParser.prototype._matchArgument"></a>[function <span class="apidocSignatureSpan">argparse.ArgumentParser.prototype.</span>_matchArgument (action, regexpArgStrings)](#apidoc.element.argparse.ArgumentParser.prototype._matchArgument)
- description and source-code
```javascript
_matchArgument = function (action, regexpArgStrings) {

  // match the pattern for this action to the arg strings
  var regexpNargs = new RegExp('^' + this._getNargsPattern(action));
  var matches = regexpArgStrings.match(regexpNargs);
  var message;

  // throw an exception if we weren't able to find a match
  if (!matches) {
    switch (action.nargs) {
<span class="apidocCodeCommentSpan">      /*eslint-disable no-undefined*/
</span>      case undefined:
      case null:
        message = 'Expected one argument.';
        break;
      case c.OPTIONAL:
        message = 'Expected at most one argument.';
        break;
      case c.ONE_OR_MORE:
        message = 'Expected at least one argument.';
        break;
      default:
        message = 'Expected %s argument(s)';
    }

    throw argumentErrorHelper(
      action,
      format(message, action.nargs)
    );
  }
  // return the number of arguments matched
  return matches[1].length;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.ArgumentParser.prototype._matchArgumentsPartial"></a>[function <span class="apidocSignatureSpan">argparse.ArgumentParser.prototype.</span>_matchArgumentsPartial (actions, regexpArgStrings)](#apidoc.element.argparse.ArgumentParser.prototype._matchArgumentsPartial)
- description and source-code
```javascript
_matchArgumentsPartial = function (actions, regexpArgStrings) {
  // progressively shorten the actions list by slicing off the
  // final actions until we find a match
  var self = this;
  var result = [];
  var actionSlice, pattern, matches;
  var i, j;

  function getLength(string) {
    return string.length;
  }

  for (i = actions.length; i > 0; i--) {
    pattern = '';
    actionSlice = actions.slice(0, i);
    for (j = 0; j < actionSlice.length; j++) {
      pattern += self._getNargsPattern(actionSlice[j]);
    }

    pattern = new RegExp('^' + pattern);
    matches = regexpArgStrings.match(pattern);

    if (matches && matches.length > 0) {
      // need only groups
      matches = matches.splice(1);
      result = result.concat(matches.map(getLength));
      break;
    }
  }

  // return the list of arg string counts
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.ArgumentParser.prototype._parseKnownArgs"></a>[function <span class="apidocSignatureSpan">argparse.ArgumentParser.prototype.</span>_parseKnownArgs (argStrings, namespace)](#apidoc.element.argparse.ArgumentParser.prototype._parseKnownArgs)
- description and source-code
```javascript
_parseKnownArgs = function (argStrings, namespace) {
  var self = this;

  var extras = [];

  // replace arg strings that are file references
  if (this.fromfilePrefixChars !== null) {
    argStrings = this._readArgsFromFiles(argStrings);
  }
  // map all mutually exclusive arguments to the other arguments
  // they can't occur with
  // Python has 'conflicts = action_conflicts.setdefault(mutex_action, [])'
  // though I can't conceive of a way in which an action could be a member
  // of two different mutually exclusive groups.

  function actionHash(action) {
    // some sort of hashable key for this action
    // action itself cannot be a key in actionConflicts
    // I think getName() (join of optionStrings) is unique enough
    return action.getName();
  }

  var conflicts, key;
  var actionConflicts = {};

  this._mutuallyExclusiveGroups.forEach(function (mutexGroup) {
    mutexGroup._groupActions.forEach(function (mutexAction, i, groupActions) {
      key = actionHash(mutexAction);
      if (!$$.has(actionConflicts, key)) {
        actionConflicts[key] = [];
      }
      conflicts = actionConflicts[key];
      conflicts.push.apply(conflicts, groupActions.slice(0, i));
      conflicts.push.apply(conflicts, groupActions.slice(i + 1));
    });
  });

  // find all option indices, and determine the arg_string_pattern
  // which has an 'O' if there is an option at an index,
  // an 'A' if there is an argument, or a '-' if there is a '--'
  var optionStringIndices = {};

  var argStringPatternParts = [];

  argStrings.forEach(function (argString, argStringIndex) {
    if (argString === '--') {
      argStringPatternParts.push('-');
      while (argStringIndex < argStrings.length) {
        argStringPatternParts.push('A');
        argStringIndex++;
      }
    } else {
      // otherwise, add the arg to the arg strings
      // and note the index if it was an option
      var pattern;
      var optionTuple = self._parseOptional(argString);
      if (!optionTuple) {
        pattern = 'A';
      } else {
        optionStringIndices[argStringIndex] = optionTuple;
        pattern = 'O';
      }
      argStringPatternParts.push(pattern);
    }
  });
  var argStringsPattern = argStringPatternParts.join('');

  var seenActions = [];
  var seenNonDefaultActions = [];


  function takeAction(action, argumentStrings, optionString) {
    seenActions.push(action);
    var argumentValues = self._getValues(action, argumentStrings);

    // error if this argument is not allowed with other previously
    // seen arguments, assuming that actions that use the default
    // value don't really count as "present"
    if (argumentValues !== action.defaultValue) {
      seenNonDefaultActions.push(action);
      if (actionConflicts[actionHash(action)]) {
        actionConflicts[actionHash(action)].forEach(function (actionConflict) {
          if (seenNonDefaultActions.indexOf(actionConflict) >= 0) {
            throw argumentErrorHelper(
              action,
              format('Not allowed with argument "%s".', actionConflict.getName())
            );
          }
        });
      }
    }

    if (argumentValues !== c.SUPPRESS) {
      action.call(self, namespace, argumentValues, optionString);
    }
  }

  function consumeOptional(startIndex) {
    // get the optional identified at this index
    var optionTuple = optionStringIndices[startIndex];
    var action = optionTuple[0];
    var optionString = optionTuple[1];
    var explicitArg = optionTuple[2];

    // identify additional optionals in the same arg string
    // (e.g. -xyz is the same as -x -y -z if no args are required)
    var actionTuples = [];

    var args, argCount, start, stop;

    for (;;) {
      if (!action) {
        extras.push(argStrings[startIndex]);
        return startIndex + 1;
      }
      if (explicitArg) {
        argCount = self._matchArgument(action, 'A');

        // if the action is a single-dash option and takes no
        // arguments, try to parse more single-dash options out
        // of the tail of the option string
        var chars = self.prefixChars;
        if ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.ArgumentParser.prototype._parseOptional"></a>[function <span class="apidocSignatureSpan">argparse.ArgumentParser.prototype.</span>_parseOptional (argString)](#apidoc.element.argparse.ArgumentParser.prototype._parseOptional)
- description and source-code
```javascript
_parseOptional = function (argString) {
  var action, optionString, argExplicit, optionTuples;

  // if it's an empty string, it was meant to be a positional
  if (!argString) {
    return null;
  }

  // if it doesn't start with a prefix, it was meant to be positional
  if (this.prefixChars.indexOf(argString[0]) < 0) {
    return null;
  }

  // if the option string is present in the parser, return the action
  if (this._optionStringActions[argString]) {
    return [ this._optionStringActions[argString], argString, null ];
  }

  // if it's just a single character, it was meant to be positional
  if (argString.length === 1) {
    return null;
  }

  // if the option string before the "=" is present, return the action
  if (argString.indexOf('=') >= 0) {
    optionString = argString.split('=', 1)[0];
    argExplicit = argString.slice(optionString.length + 1);

    if (this._optionStringActions[optionString]) {
      action = this._optionStringActions[optionString];
      return [ action, optionString, argExplicit ];
    }
  }

  // search through all possible prefixes of the option string
  // and all actions in the parser for possible interpretations
  optionTuples = this._getOptionTuples(argString);

  // if multiple actions match, the option string was ambiguous
  if (optionTuples.length > 1) {
    var optionStrings = optionTuples.map(function (optionTuple) {
      return optionTuple[1];
    });
    this.error(format(
          'Ambiguous option: "%s" could match %s.',
          argString, optionStrings.join(', ')
    ));
  // if exactly one action matched, this segmentation is good,
  // so return the parsed action
  } else if (optionTuples.length === 1) {
    return optionTuples[0];
  }

  // if it was not found as an option, but it looks like a negative
  // number, it was meant to be positional
  // unless there are negative-number-like options
  if (argString.match(this._regexpNegativeNumber)) {
    if (!this._hasNegativeNumberOptionals.some(Boolean)) {
      return null;
    }
  }
  // if it contains a space, it was meant to be a positional
  if (argString.search(' ') >= 0) {
    return null;
  }

  // it was meant to be an optional but there is no such option
  // in this parser (though it might be a valid option in a subparser)
  return [ null, argString, null ];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.ArgumentParser.prototype._printMessage"></a>[function <span class="apidocSignatureSpan">argparse.ArgumentParser.prototype.</span>_printMessage (message, stream)](#apidoc.element.argparse.ArgumentParser.prototype._printMessage)
- description and source-code
```javascript
_printMessage = function (message, stream) {
  if (!stream) {
    stream = process.stdout;
  }
  if (message) {
    stream.write('' + message);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.ArgumentParser.prototype._readArgsFromFiles"></a>[function <span class="apidocSignatureSpan">argparse.ArgumentParser.prototype.</span>_readArgsFromFiles (argStrings)](#apidoc.element.argparse.ArgumentParser.prototype._readArgsFromFiles)
- description and source-code
```javascript
_readArgsFromFiles = function (argStrings) {
  // expand arguments referencing files
  var self = this;
  var fs = require('fs');
  var newArgStrings = [];
  argStrings.forEach(function (argString) {
    if (self.fromfilePrefixChars.indexOf(argString[0]) < 0) {
      // for regular arguments, just add them back into the list
      newArgStrings.push(argString);
    } else {
      // replace arguments referencing files with the file content
      try {
        var argstrs = [];
        var filename = argString.slice(1);
        var content = fs.readFileSync(filename, 'utf8');
        content = content.trim().split('\n');
        content.forEach(function (argLine) {
          self.convertArgLineToArgs(argLine).forEach(function (arg) {
            argstrs.push(arg);
          });
          argstrs = self._readArgsFromFiles(argstrs);
        });
        newArgStrings.push.apply(newArgStrings, argstrs);
      } catch (error) {
        return self.error(error.message);
      }
    }
  });
  return newArgStrings;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.ArgumentParser.prototype.addSubparsers"></a>[function <span class="apidocSignatureSpan">argparse.ArgumentParser.prototype.</span>addSubparsers (options)](#apidoc.element.argparse.ArgumentParser.prototype.addSubparsers)
- description and source-code
```javascript
addSubparsers = function (options) {
  if (this._subparsers) {
    this.error('Cannot have multiple subparser arguments.');
  }

  options = options || {};
  options.debug = (this.debug === true);
  options.optionStrings = [];
  options.parserClass = (options.parserClass || ArgumentParser);


  if (!!options.title || !!options.description) {

    this._subparsers = this.addArgumentGroup({
      title: (options.title || 'subcommands'),
      description: options.description
    });
    delete options.title;
    delete options.description;

  } else {
    this._subparsers = this._positionals;
  }

  // prog defaults to the usage message of this parser, skipping
  // optional arguments and with no "usage:" prefix
  if (!options.prog) {
    var formatter = this._getFormatter();
    var positionals = this._getPositionalActions();
    var groups = this._mutuallyExclusiveGroups;
    formatter.addUsage(this.usage, positionals, groups, '');
    options.prog = formatter.formatHelp().trim();
  }

  // create the parsers action and add it to the positionals list
  var ParsersClass = this._popActionClass(options, 'parsers');
  var action = new ParsersClass(options);
  this._subparsers._addAction(action);

  // return the created parsers action
  return action;
}
```
- example usage
```shell
...

Details in [original action guide](http://docs.python.org/dev/library/argparse.html#action)


Sub-commands
============

ArgumentParser.addSubparsers()

Many programs split their functionality into a number of sub-commands, for
example, the svn program can invoke sub-commands like 'svn checkout', 'svn update',
and 'svn commit'. Splitting up functionality this way can be a particularly good
idea when a program performs several different functions which require different
kinds of command-line arguments. 'ArgumentParser' supports creation of such
sub-commands with 'addSubparsers()' method. The 'addSubparsers()' method is
...
```

#### <a name="apidoc.element.argparse.ArgumentParser.prototype.convertArgLineToArgs"></a>[function <span class="apidocSignatureSpan">argparse.ArgumentParser.prototype.</span>convertArgLineToArgs (argLine)](#apidoc.element.argparse.ArgumentParser.prototype.convertArgLineToArgs)
- description and source-code
```javascript
convertArgLineToArgs = function (argLine) {
  return [ argLine ];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.ArgumentParser.prototype.error"></a>[function <span class="apidocSignatureSpan">argparse.ArgumentParser.prototype.</span>error (err)](#apidoc.element.argparse.ArgumentParser.prototype.error)
- description and source-code
```javascript
error = function (err) {
  var message;
  if (err instanceof Error) {
    if (this.debug === true) {
      throw err;
    }
    message = err.message;
  } else {
    message = err;
  }
  var msg = format('%s: error: %s', this.prog, message) + c.EOL;

  if (this.debug === true) {
    throw new Error(msg);
  }

  this.printUsage(process.stderr);

  return this.exit(2, msg);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.ArgumentParser.prototype.exit"></a>[function <span class="apidocSignatureSpan">argparse.ArgumentParser.prototype.</span>exit (status, message)](#apidoc.element.argparse.ArgumentParser.prototype.exit)
- description and source-code
```javascript
exit = function (status, message) {
  if (message) {
    if (status === 0) {
      this._printMessage(message);
    } else {
      this._printMessage(message, process.stderr);
    }
  }

  process.exit(status);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.ArgumentParser.prototype.formatHelp"></a>[function <span class="apidocSignatureSpan">argparse.ArgumentParser.prototype.</span>formatHelp ()](#apidoc.element.argparse.ArgumentParser.prototype.formatHelp)
- description and source-code
```javascript
formatHelp = function () {
  var formatter = this._getFormatter();

  // usage
  formatter.addUsage(this.usage, this._actions, this._mutuallyExclusiveGroups);

  // description
  formatter.addText(this.description);

  // positionals, optionals and user-defined groups
  this._actionGroups.forEach(function (actionGroup) {
    formatter.startSection(actionGroup.title);
    formatter.addText(actionGroup.description);
    formatter.addArguments(actionGroup._groupActions);
    formatter.endSection();
  });

  // epilog
  formatter.addText(this.epilog);

  // determine help from format above
  return formatter.formatHelp();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.ArgumentParser.prototype.formatUsage"></a>[function <span class="apidocSignatureSpan">argparse.ArgumentParser.prototype.</span>formatUsage ()](#apidoc.element.argparse.ArgumentParser.prototype.formatUsage)
- description and source-code
```javascript
formatUsage = function () {
  var formatter = this._getFormatter();
  formatter.addUsage(this.usage, this._actions, this._mutuallyExclusiveGroups);
  return formatter.formatHelp();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.ArgumentParser.prototype.parseArgs"></a>[function <span class="apidocSignatureSpan">argparse.ArgumentParser.prototype.</span>parseArgs (args, namespace)](#apidoc.element.argparse.ArgumentParser.prototype.parseArgs)
- description and source-code
```javascript
parseArgs = function (args, namespace) {
  var argv;
  var result = this.parseKnownArgs(args, namespace);

  args = result[0];
  argv = result[1];
  if (argv && argv.length > 0) {
    this.error(
      format('Unrecognized arguments: %s.', argv.join(' '))
    );
  }
  return args;
}
```
- example usage
```shell
...
);
parser.addArgument(
  '--baz',
  {
    help: 'baz bar'
  }
);
var args = parser.parseArgs();
console.dir(args);
'''

Display help:

'''
$ ./test.js -h
...
```

#### <a name="apidoc.element.argparse.ArgumentParser.prototype.parseKnownArgs"></a>[function <span class="apidocSignatureSpan">argparse.ArgumentParser.prototype.</span>parseKnownArgs (args, namespace)](#apidoc.element.argparse.ArgumentParser.prototype.parseKnownArgs)
- description and source-code
```javascript
parseKnownArgs = function (args, namespace) {
  var self = this;

  // args default to the system args
  args = args || process.argv.slice(2);

  // default Namespace built from parser defaults
  namespace = namespace || new Namespace();

  self._actions.forEach(function (action) {
    if (action.dest !== c.SUPPRESS) {
      if (!$$.has(namespace, action.dest)) {
        if (action.defaultValue !== c.SUPPRESS) {
          var defaultValue = action.defaultValue;
          if (typeof action.defaultValue === 'string') {
            defaultValue = self._getValue(action, defaultValue);
          }
          namespace[action.dest] = defaultValue;
        }
      }
    }
  });

  Object.keys(self._defaults).forEach(function (dest) {
    namespace[dest] = self._defaults[dest];
  });

  // parse the arguments and exit if there are any errors
  try {
    var res = this._parseKnownArgs(args, namespace);

    namespace = res[0];
    args = res[1];
    if ($$.has(namespace, c._UNRECOGNIZED_ARGS_ATTR)) {
      args = $$.arrayUnion(args, namespace[c._UNRECOGNIZED_ARGS_ATTR]);
      delete namespace[c._UNRECOGNIZED_ARGS_ATTR];
    }
    return [ namespace, args ];
  } catch (e) {
    this.error(e);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.ArgumentParser.prototype.printHelp"></a>[function <span class="apidocSignatureSpan">argparse.ArgumentParser.prototype.</span>printHelp ()](#apidoc.element.argparse.ArgumentParser.prototype.printHelp)
- description and source-code
```javascript
printHelp = function () {
  this._printMessage(this.formatHelp());
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.ArgumentParser.prototype.printUsage"></a>[function <span class="apidocSignatureSpan">argparse.ArgumentParser.prototype.</span>printUsage ()](#apidoc.element.argparse.ArgumentParser.prototype.printUsage)
- description and source-code
```javascript
printUsage = function () {
  this._printMessage(this.formatUsage());
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.argparse.ArgumentParser.super_"></a>[module argparse.ArgumentParser.super_](#apidoc.module.argparse.ArgumentParser.super_)

#### <a name="apidoc.element.argparse.ArgumentParser.super_.super_"></a>[function <span class="apidocSignatureSpan">argparse.ArgumentParser.</span>super_ (options)](#apidoc.element.argparse.ArgumentParser.super_.super_)
- description and source-code
```javascript
function ActionContainer(options) {
  options = options || {};

  this.description = options.description;
  this.argumentDefault = options.argumentDefault;
  this.prefixChars = options.prefixChars || '';
  this.conflictHandler = options.conflictHandler;

  // set up registries
  this._registries = {};

  // register actions
  this.register('action', null, ActionStore);
  this.register('action', 'store', ActionStore);
  this.register('action', 'storeConst', ActionStoreConstant);
  this.register('action', 'storeTrue', ActionStoreTrue);
  this.register('action', 'storeFalse', ActionStoreFalse);
  this.register('action', 'append', ActionAppend);
  this.register('action', 'appendConst', ActionAppendConstant);
  this.register('action', 'count', ActionCount);
  this.register('action', 'help', ActionHelp);
  this.register('action', 'version', ActionVersion);
  this.register('action', 'parsers', ActionSubparsers);

  // raise an exception if the conflict handler is invalid
  this._getHandler();

  // action storage
  this._actions = [];
  this._optionStringActions = {};

  // groups
  this._actionGroups = [];
  this._mutuallyExclusiveGroups = [];

  // defaults storage
  this._defaults = {};

  // determines whether an "option" looks like a negative number
  // -1, -1.5 -5e+4
  this._regexpNegativeNumber = new RegExp('^[-]?[0-9]*\\.?[0-9]+([eE][-+]?[0-9]+)?$');

  // whether or not there are any optionals that look like negative
  // numbers -- uses a list so it can be shared and edited
  this._hasNegativeNumberOptionals = [];
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.argparse.ArgumentParser.super_.prototype"></a>[module argparse.ArgumentParser.super_.prototype](#apidoc.module.argparse.ArgumentParser.super_.prototype)

#### <a name="apidoc.element.argparse.ArgumentParser.super_.prototype._addAction"></a>[function <span class="apidocSignatureSpan">argparse.ArgumentParser.super_.prototype.</span>_addAction (action)](#apidoc.element.argparse.ArgumentParser.super_.prototype._addAction)
- description and source-code
```javascript
_addAction = function (action) {
  var self = this;

  // resolve any conflicts
  this._checkConflict(action);

  // add to actions list
  this._actions.push(action);
  action.container = this;

  // index the action by any option strings it has
  action.optionStrings.forEach(function (optionString) {
    self._optionStringActions[optionString] = action;
  });

  // set the flag if any option strings look like negative numbers
  action.optionStrings.forEach(function (optionString) {
    if (optionString.match(self._regexpNegativeNumber)) {
      if (!self._hasNegativeNumberOptionals.some(Boolean)) {
        self._hasNegativeNumberOptionals.push(true);
      }
    }
  });

  // return the created action
  return action;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.ArgumentParser.super_.prototype._addContainerActions"></a>[function <span class="apidocSignatureSpan">argparse.ArgumentParser.super_.prototype.</span>_addContainerActions (container)](#apidoc.element.argparse.ArgumentParser.super_.prototype._addContainerActions)
- description and source-code
```javascript
_addContainerActions = function (container) {
  // collect groups by titles
  var titleGroupMap = {};
  this._actionGroups.forEach(function (group) {
    if (titleGroupMap[group.title]) {
      throw new Error(format('Cannot merge actions - two groups are named "%s".', group.title));
    }
    titleGroupMap[group.title] = group;
  });

  // map each action to its group
  var groupMap = {};
  function actionHash(action) {
    // unique (hopefully?) string suitable as dictionary key
    return action.getName();
  }
  container._actionGroups.forEach(function (group) {
    // if a group with the title exists, use that, otherwise
    // create a new group matching the container's group
    if (!titleGroupMap[group.title]) {
      titleGroupMap[group.title] = this.addArgumentGroup({
        title: group.title,
        description: group.description
      });
    }

    // map the actions to their new group
    group._groupActions.forEach(function (action) {
      groupMap[actionHash(action)] = titleGroupMap[group.title];
    });
  }, this);

  // add container's mutually exclusive groups
  // NOTE: if add_mutually_exclusive_group ever gains title= and
  // description= then this code will need to be expanded as above
  var mutexGroup;
  container._mutuallyExclusiveGroups.forEach(function (group) {
    mutexGroup = this.addMutuallyExclusiveGroup({
      required: group.required
    });
    // map the actions to their new mutex group
    group._groupActions.forEach(function (action) {
      groupMap[actionHash(action)] = mutexGroup;
    });
  }, this);  // forEach takes a 'this' argument

  // add all actions to this container or their group
  container._actions.forEach(function (action) {
    var key = actionHash(action);
    if (groupMap[key]) {
      groupMap[key]._addAction(action);
    } else {
      this._addAction(action);
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.ArgumentParser.super_.prototype._checkConflict"></a>[function <span class="apidocSignatureSpan">argparse.ArgumentParser.super_.prototype.</span>_checkConflict (action)](#apidoc.element.argparse.ArgumentParser.super_.prototype._checkConflict)
- description and source-code
```javascript
_checkConflict = function (action) {
  var optionStringActions = this._optionStringActions;
  var conflictOptionals = [];

  // find all options that conflict with this option
  // collect pairs, the string, and an existing action that it conflicts with
  action.optionStrings.forEach(function (optionString) {
    var conflOptional = optionStringActions[optionString];
    if (typeof conflOptional !== 'undefined') {
      conflictOptionals.push([ optionString, conflOptional ]);
    }
  });

  if (conflictOptionals.length > 0) {
    var conflictHandler = this._getHandler();
    conflictHandler.call(this, action, conflictOptionals);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.ArgumentParser.super_.prototype._getHandler"></a>[function <span class="apidocSignatureSpan">argparse.ArgumentParser.super_.prototype.</span>_getHandler ()](#apidoc.element.argparse.ArgumentParser.super_.prototype._getHandler)
- description and source-code
```javascript
_getHandler = function () {
  var handlerString = this.conflictHandler;
  var handlerFuncName = '_handleConflict' + $$.capitalize(handlerString);
  var func = this[handlerFuncName];
  if (typeof func === 'undefined') {
    var msg = 'invalid conflict resolution value: ' + handlerString;
    throw new Error(msg);
  } else {
    return func;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.ArgumentParser.super_.prototype._getOptional"></a>[function <span class="apidocSignatureSpan">argparse.ArgumentParser.super_.prototype.</span>_getOptional (args, options)](#apidoc.element.argparse.ArgumentParser.super_.prototype._getOptional)
- description and source-code
```javascript
_getOptional = function (args, options) {
  var prefixChars = this.prefixChars;
  var optionStrings = [];
  var optionStringsLong = [];

  // determine short and long option strings
  args.forEach(function (optionString) {
    // error on strings that don't start with an appropriate prefix
    if (prefixChars.indexOf(optionString[0]) < 0) {
      throw new Error(format('Invalid option string "%s": must start with a "%s".',
        optionString,
        prefixChars
      ));
    }

    // strings starting with two prefix characters are long options
    optionStrings.push(optionString);
    if (optionString.length > 1 && prefixChars.indexOf(optionString[1]) >= 0) {
      optionStringsLong.push(optionString);
    }
  });

  // infer dest, '--foo-bar' -> 'foo_bar' and '-x' -> 'x'
  var dest = options.dest || null;
  delete options.dest;

  if (!dest) {
    var optionStringDest = optionStringsLong.length ? optionStringsLong[0] : optionStrings[0];
    dest = $$.trimChars(optionStringDest, this.prefixChars);

    if (dest.length === 0) {
      throw new Error(
        format('dest= is required for options like "%s"', optionStrings.join(', '))
      );
    }
    dest = dest.replace(/-/g, '_');
  }

  // return the updated keyword arguments
  options.dest = dest;
  options.optionStrings = optionStrings;

  return options;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.ArgumentParser.super_.prototype._getPositional"></a>[function <span class="apidocSignatureSpan">argparse.ArgumentParser.super_.prototype.</span>_getPositional (dest, options)](#apidoc.element.argparse.ArgumentParser.super_.prototype._getPositional)
- description and source-code
```javascript
_getPositional = function (dest, options) {
  if (Array.isArray(dest)) {
    dest = dest[0];
  }
  // make sure required is not specified
  if (options.required) {
    throw new Error('"required" is an invalid argument for positionals.');
  }

  // mark positional arguments as required if at least one is
  // always required
  if (options.nargs !== c.OPTIONAL && options.nargs !== c.ZERO_OR_MORE) {
    options.required = true;
  }
  if (options.nargs === c.ZERO_OR_MORE && typeof options.defaultValue === 'undefined') {
    options.required = true;
  }

  // return the keyword arguments with no option strings
  options.dest = dest;
  options.optionStrings = [];
  return options;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.ArgumentParser.super_.prototype._handleConflictError"></a>[function <span class="apidocSignatureSpan">argparse.ArgumentParser.super_.prototype.</span>_handleConflictError (action, conflOptionals)](#apidoc.element.argparse.ArgumentParser.super_.prototype._handleConflictError)
- description and source-code
```javascript
_handleConflictError = function (action, conflOptionals) {
  var conflicts = conflOptionals.map(function (pair) { return pair[0]; });
  conflicts = conflicts.join(', ');
  throw argumentErrorHelper(
    action,
    format('Conflicting option string(s): %s', conflicts)
  );
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.ArgumentParser.super_.prototype._handleConflictResolve"></a>[function <span class="apidocSignatureSpan">argparse.ArgumentParser.super_.prototype.</span>_handleConflictResolve (action, conflOptionals)](#apidoc.element.argparse.ArgumentParser.super_.prototype._handleConflictResolve)
- description and source-code
```javascript
_handleConflictResolve = function (action, conflOptionals) {
  // remove all conflicting options
  var self = this;
  conflOptionals.forEach(function (pair) {
    var optionString = pair[0];
    var conflictingAction = pair[1];
    // remove the conflicting option string
    var i = conflictingAction.optionStrings.indexOf(optionString);
    if (i >= 0) {
      conflictingAction.optionStrings.splice(i, 1);
    }
    delete self._optionStringActions[optionString];
    // if the option now has no option string, remove it from the
    // container holding it
    if (conflictingAction.optionStrings.length === 0) {
      conflictingAction.container._removeAction(conflictingAction);
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.ArgumentParser.super_.prototype._popActionClass"></a>[function <span class="apidocSignatureSpan">argparse.ArgumentParser.super_.prototype.</span>_popActionClass (options, defaultValue)](#apidoc.element.argparse.ArgumentParser.super_.prototype._popActionClass)
- description and source-code
```javascript
_popActionClass = function (options, defaultValue) {
  defaultValue = defaultValue || null;

  var action = (options.action || defaultValue);
  delete options.action;

  var actionClass = this._registryGet('action', action, action);
  return actionClass;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.ArgumentParser.super_.prototype._registryGet"></a>[function <span class="apidocSignatureSpan">argparse.ArgumentParser.super_.prototype.</span>_registryGet (registryName, value, defaultValue)](#apidoc.element.argparse.ArgumentParser.super_.prototype._registryGet)
- description and source-code
```javascript
_registryGet = function (registryName, value, defaultValue) {
  if (arguments.length < 3) {
    defaultValue = null;
  }
  return this._registries[registryName][value] || defaultValue;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.ArgumentParser.super_.prototype._removeAction"></a>[function <span class="apidocSignatureSpan">argparse.ArgumentParser.super_.prototype.</span>_removeAction (action)](#apidoc.element.argparse.ArgumentParser.super_.prototype._removeAction)
- description and source-code
```javascript
_removeAction = function (action) {
  var actionIndex = this._actions.indexOf(action);
  if (actionIndex >= 0) {
    this._actions.splice(actionIndex, 1);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.ArgumentParser.super_.prototype.addArgument"></a>[function <span class="apidocSignatureSpan">argparse.ArgumentParser.super_.prototype.</span>addArgument (args, options)](#apidoc.element.argparse.ArgumentParser.super_.prototype.addArgument)
- description and source-code
```javascript
addArgument = function (args, options) {
  args = args;
  options = options || {};

  if (typeof args === 'string') {
    args = [ args ];
  }
  if (!Array.isArray(args)) {
    throw new TypeError('addArgument first argument should be a string or an array');
  }
  if (typeof options !== 'object' || Array.isArray(options)) {
    throw new TypeError('addArgument second argument should be a hash');
  }

  // if no positional args are supplied or only one is supplied and
  // it doesn't look like an option string, parse a positional argument
  if (!args || args.length === 1 && this.prefixChars.indexOf(args[0][0]) < 0) {
    if (args && !!options.dest) {
      throw new Error('dest supplied twice for positional argument');
    }
    options = this._getPositional(args, options);

    // otherwise, we're adding an optional argument
  } else {
    options = this._getOptional(args, options);
  }

  // if no default was supplied, use the parser-level default
  if (typeof options.defaultValue === 'undefined') {
    var dest = options.dest;
    if ($$.has(this._defaults, dest)) {
      options.defaultValue = this._defaults[dest];
    } else if (typeof this.argumentDefault !== 'undefined') {
      options.defaultValue = this.argumentDefault;
    }
  }

  // create the action object, and add it to the parser
  var ActionClass = this._popActionClass(options);
  if (typeof ActionClass !== 'function') {
    throw new Error(format('Unknown action "%s".', ActionClass));
  }
  var action = new ActionClass(options);

  // throw an error if the action type is not callable
  var typeFunction = this._registryGet('type', action.type, action.type);
  if (typeof typeFunction !== 'function') {
    throw new Error(format('"%s" is not callable', typeFunction));
  }

  return this._addAction(action);
}
```
- example usage
```shell
...

var ArgumentParser = require('../lib/argparse').ArgumentParser;
var parser = new ArgumentParser({
version: '0.0.1',
addHelp:true,
description: 'Argparse example'
});
parser.addArgument(
[ '-f', '--foo' ],
{
  help: 'foo bar'
}
);
parser.addArgument(
[ '-b', '--bar' ],
...
```

#### <a name="apidoc.element.argparse.ArgumentParser.super_.prototype.addArgumentGroup"></a>[function <span class="apidocSignatureSpan">argparse.ArgumentParser.super_.prototype.</span>addArgumentGroup (options)](#apidoc.element.argparse.ArgumentParser.super_.prototype.addArgumentGroup)
- description and source-code
```javascript
addArgumentGroup = function (options) {
  var group = new ArgumentGroup(this, options);
  this._actionGroups.push(group);
  return group;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.ArgumentParser.super_.prototype.addMutuallyExclusiveGroup"></a>[function <span class="apidocSignatureSpan">argparse.ArgumentParser.super_.prototype.</span>addMutuallyExclusiveGroup (options)](#apidoc.element.argparse.ArgumentParser.super_.prototype.addMutuallyExclusiveGroup)
- description and source-code
```javascript
addMutuallyExclusiveGroup = function (options) {
  var group = new MutuallyExclusiveGroup(this, options);
  this._mutuallyExclusiveGroups.push(group);
  return group;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.ArgumentParser.super_.prototype.getDefault"></a>[function <span class="apidocSignatureSpan">argparse.ArgumentParser.super_.prototype.</span>getDefault (dest)](#apidoc.element.argparse.ArgumentParser.super_.prototype.getDefault)
- description and source-code
```javascript
getDefault = function (dest) {
  var result = $$.has(this._defaults, dest) ? this._defaults[dest] : null;

  this._actions.forEach(function (action) {
    if (action.dest === dest && $$.has(action, 'defaultValue')) {
      result = action.defaultValue;
    }
  });

  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.ArgumentParser.super_.prototype.register"></a>[function <span class="apidocSignatureSpan">argparse.ArgumentParser.super_.prototype.</span>register (registryName, value, object)](#apidoc.element.argparse.ArgumentParser.super_.prototype.register)
- description and source-code
```javascript
register = function (registryName, value, object) {
  this._registries[registryName] = this._registries[registryName] || {};
  this._registries[registryName][value] = object;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.ArgumentParser.super_.prototype.setDefaults"></a>[function <span class="apidocSignatureSpan">argparse.ArgumentParser.super_.prototype.</span>setDefaults (options)](#apidoc.element.argparse.ArgumentParser.super_.prototype.setDefaults)
- description and source-code
```javascript
setDefaults = function (options) {
  options = options || {};
  for (var property in options) {
    if ($$.has(options, property)) {
      this._defaults[property] = options[property];
    }
  }

  // if these defaults match any existing arguments, replace the previous
  // default on the object with the new one
  this._actions.forEach(function (action) {
    if ($$.has(options, action.dest)) {
      action.defaultValue = options[action.dest];
    }
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.argparse.HelpFormatter"></a>[module argparse.HelpFormatter](#apidoc.module.argparse.HelpFormatter)

#### <a name="apidoc.element.argparse.HelpFormatter.HelpFormatter"></a>[function <span class="apidocSignatureSpan">argparse.</span>HelpFormatter (options)](#apidoc.element.argparse.HelpFormatter.HelpFormatter)
- description and source-code
```javascript
function HelpFormatter(options) {
  options = options || {};

  this._prog = options.prog;

  this._maxHelpPosition = options.maxHelpPosition || 24;
  this._width = (options.width || ((process.env.COLUMNS || 80) - 2));

  this._currentIndent = 0;
  this._indentIncriment = options.indentIncriment || 2;
  this._level = 0;
  this._actionMaxLength = 0;

  this._rootSection = new Section(null);
  this._currentSection = this._rootSection;

  this._whitespaceMatcher = new RegExp('\\s+', 'g');
  this._longBreakMatcher = new RegExp(c.EOL + c.EOL + c.EOL + '+', 'g');
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.argparse.HelpFormatter.prototype"></a>[module argparse.HelpFormatter.prototype](#apidoc.module.argparse.HelpFormatter.prototype)

#### <a name="apidoc.element.argparse.HelpFormatter.prototype._addItem"></a>[function <span class="apidocSignatureSpan">argparse.HelpFormatter.prototype.</span>_addItem (func, args)](#apidoc.element.argparse.HelpFormatter.prototype._addItem)
- description and source-code
```javascript
_addItem = function (func, args) {
  this._currentSection.addItem([ func, args ]);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.HelpFormatter.prototype._dedent"></a>[function <span class="apidocSignatureSpan">argparse.HelpFormatter.prototype.</span>_dedent ()](#apidoc.element.argparse.HelpFormatter.prototype._dedent)
- description and source-code
```javascript
_dedent = function () {
  this._currentIndent -= this._indentIncriment;
  this._level -= 1;
  if (this._currentIndent < 0) {
    throw new Error('Indent decreased below 0.');
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.HelpFormatter.prototype._expandHelp"></a>[function <span class="apidocSignatureSpan">argparse.HelpFormatter.prototype.</span>_expandHelp (action)](#apidoc.element.argparse.HelpFormatter.prototype._expandHelp)
- description and source-code
```javascript
_expandHelp = function (action) {
  var params = { prog: this._prog };

  Object.keys(action).forEach(function (actionProperty) {
    var actionValue = action[actionProperty];

    if (actionValue !== c.SUPPRESS) {
      params[actionProperty] = actionValue;
    }
  });

  if (params.choices) {
    if (typeof params.choices === 'string') {
      params.choices = params.choices.split('').join(', ');
    } else if (Array.isArray(params.choices)) {
      params.choices = params.choices.join(', ');
    } else {
      params.choices = Object.keys(params.choices).join(', ');
    }
  }

  return sprintf(this._getHelpString(action), params);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.HelpFormatter.prototype._fillText"></a>[function <span class="apidocSignatureSpan">argparse.HelpFormatter.prototype.</span>_fillText (text, width, indent)](#apidoc.element.argparse.HelpFormatter.prototype._fillText)
- description and source-code
```javascript
_fillText = function (text, width, indent) {
  var lines = this._splitLines(text, width);
  lines = lines.map(function (line) {
    return indent + line;
  });
  return lines.join(c.EOL);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.HelpFormatter.prototype._formatAction"></a>[function <span class="apidocSignatureSpan">argparse.HelpFormatter.prototype.</span>_formatAction (action)](#apidoc.element.argparse.HelpFormatter.prototype._formatAction)
- description and source-code
```javascript
_formatAction = function (action) {
  var self = this;

  var helpText;
  var helpLines;
  var parts;
  var indentFirst;

  // determine the required width and the entry label
  var helpPosition = Math.min(this._actionMaxLength + 2, this._maxHelpPosition);
  var helpWidth = this._width - helpPosition;
  var actionWidth = helpPosition - this._currentIndent - 2;
  var actionHeader = this._formatActionInvocation(action);

  // no help; start on same line and add a final newline
  if (!action.help) {
    actionHeader = $$.repeat(' ', this._currentIndent) + actionHeader + c.EOL;

  // short action name; start on the same line and pad two spaces
  } else if (actionHeader.length <= actionWidth) {
    actionHeader = $$.repeat(' ', this._currentIndent) +
        actionHeader +
        '  ' +
        $$.repeat(' ', actionWidth - actionHeader.length);
    indentFirst = 0;

  // long action name; start on the next line
  } else {
    actionHeader = $$.repeat(' ', this._currentIndent) + actionHeader + c.EOL;
    indentFirst = helpPosition;
  }

  // collect the pieces of the action help
  parts = [ actionHeader ];

  // if there was help for the action, add lines of help text
  if (action.help) {
    helpText = this._expandHelp(action);
    helpLines = this._splitLines(helpText, helpWidth);
    parts.push($$.repeat(' ', indentFirst) + helpLines[0] + c.EOL);
    helpLines.slice(1).forEach(function (line) {
      parts.push($$.repeat(' ', helpPosition) + line + c.EOL);
    });

  // or add a newline if the description doesn't end with one
  } else if (actionHeader.charAt(actionHeader.length - 1) !== c.EOL) {
    parts.push(c.EOL);
  }
  // if there are any sub-actions, add their help as well
  if (action._getSubactions) {
    this._indent();
    action._getSubactions().forEach(function (subaction) {
      parts.push(self._formatAction(subaction));
    });
    this._dedent();
  }
  // return a single string
  return this._joinParts(parts);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.HelpFormatter.prototype._formatActionInvocation"></a>[function <span class="apidocSignatureSpan">argparse.HelpFormatter.prototype.</span>_formatActionInvocation (action)](#apidoc.element.argparse.HelpFormatter.prototype._formatActionInvocation)
- description and source-code
```javascript
_formatActionInvocation = function (action) {
  if (!action.isOptional()) {
    var format_func = this._metavarFormatter(action, action.dest);
    var metavars = format_func(1);
    return metavars[0];
  }

  var parts = [];
  var argsDefault;
  var argsString;

  // if the Optional doesn't take a value, format is: -s, --long
  if (action.nargs === 0) {
    parts = parts.concat(action.optionStrings);

  // if the Optional takes a value, format is: -s ARGS, --long ARGS
  } else {
    argsDefault = action.dest.toUpperCase();
    argsString = this._formatArgs(action, argsDefault);
    action.optionStrings.forEach(function (optionString) {
      parts.push(optionString + ' ' + argsString);
    });
  }
  return parts.join(', ');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.HelpFormatter.prototype._formatActionsUsage"></a>[function <span class="apidocSignatureSpan">argparse.HelpFormatter.prototype.</span>_formatActionsUsage (actions, groups)](#apidoc.element.argparse.HelpFormatter.prototype._formatActionsUsage)
- description and source-code
```javascript
_formatActionsUsage = function (actions, groups) {
  // find group indices and identify actions in groups
  var groupActions = [];
  var inserts = [];
  var self = this;

  groups.forEach(function (group) {
    var end;
    var i;

    var start = actions.indexOf(group._groupActions[0]);
    if (start >= 0) {
      end = start + group._groupActions.length;

      //if (actions.slice(start, end) === group._groupActions) {
      if ($$.arrayEqual(actions.slice(start, end), group._groupActions)) {
        group._groupActions.forEach(function (action) {
          groupActions.push(action);
        });

        if (!group.required) {
          if (inserts[start]) {
            inserts[start] += ' [';
          } else {
            inserts[start] = '[';
          }
          inserts[end] = ']';
        } else {
          if (inserts[start]) {
            inserts[start] += ' (';
          } else {
            inserts[start] = '(';
          }
          inserts[end] = ')';
        }
        for (i = start + 1; i < end; i += 1) {
          inserts[i] = '|';
        }
      }
    }
  });

  // collect all actions format strings
  var parts = [];

  actions.forEach(function (action, actionIndex) {
    var part;
    var optionString;
    var argsDefault;
    var argsString;

    // suppressed arguments are marked with None
    // remove | separators for suppressed arguments
    if (action.help === c.SUPPRESS) {
      parts.push(null);
      if (inserts[actionIndex] === '|') {
        inserts.splice(actionIndex, actionIndex);
      } else if (inserts[actionIndex + 1] === '|') {
        inserts.splice(actionIndex + 1, actionIndex + 1);
      }

      // produce all arg strings
    } else if (!action.isOptional()) {
      part = self._formatArgs(action, action.dest);

      // if it's in a group, strip the outer []
      if (groupActions.indexOf(action) >= 0) {
        if (part[0] === '[' && part[part.length - 1] === ']') {
          part = part.slice(1, -1);
        }
      }
      // add the action string to the list
      parts.push(part);

    // produce the first way to invoke the option in brackets
    } else {
      optionString = action.optionStrings[0];

      // if the Optional doesn't take a value, format is: -s or --long
      if (action.nargs === 0) {
        part = '' + optionString;

      // if the Optional takes a value, format is: -s ARGS or --long ARGS
      } else {
        argsDefault = action.dest.toUpperCase();
        argsString = self._formatArgs(action, argsDefault);
        part = optionString + ' ' + argsString;
      }
      // make it look optional if it's not required or in a group
      if (!action.required && groupActions.indexOf(action) < 0) {
        part = '[' + part + ']';
      }
      // add the action string to the list
      parts.push(part);
    }
  });

  // insert things at the necessary indices
  for (var i = inserts.length - 1; i >= 0; --i) {
    if (inserts[i] !== null) {
      parts.splice(i, 0, inserts[i]);
    }
  }

  // join all the action items with spaces
  var text = parts.filter(function (part) {
    return !!part;
  }).join(' ');

  // clean up separators for mutually exclusive groups
  text = text.replace(/([\[(]) /g, '$1'); // remove spaces
  text = text.replace(/ ([\])])/g, '$1');
  text = text.replace(/\[ *\]/g, ''); // remove empty groups
  text = text.replace(/\( *\)/g, '');
  text = text.replace(/\(([^|]*)\)/g, '$1'); // remove () from single action groups

  text = text.trim();

  // return the text
  return text;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.HelpFormatter.prototype._formatArgs"></a>[function <span class="apidocSignatureSpan">argparse.HelpFormatter.prototype.</span>_formatArgs (action, metavarDefault)](#apidoc.element.argparse.HelpFormatter.prototype._formatArgs)
- description and source-code
```javascript
_formatArgs = function (action, metavarDefault) {
  var result;
  var metavars;

  var buildMetavar = this._metavarFormatter(action, metavarDefault);

  switch (action.nargs) {
<span class="apidocCodeCommentSpan">    /*eslint-disable no-undefined*/
</span>    case undefined:
    case null:
      metavars = buildMetavar(1);
      result = '' + metavars[0];
      break;
    case c.OPTIONAL:
      metavars = buildMetavar(1);
      result = '[' + metavars[0] + ']';
      break;
    case c.ZERO_OR_MORE:
      metavars = buildMetavar(2);
      result = '[' + metavars[0] + ' [' + metavars[1] + ' ...]]';
      break;
    case c.ONE_OR_MORE:
      metavars = buildMetavar(2);
      result = '' + metavars[0] + ' [' + metavars[1] + ' ...]';
      break;
    case c.REMAINDER:
      result = '...';
      break;
    case c.PARSER:
      metavars = buildMetavar(1);
      result = metavars[0] + ' ...';
      break;
    default:
      metavars = buildMetavar(action.nargs);
      result = metavars.join(' ');
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.HelpFormatter.prototype._formatText"></a>[function <span class="apidocSignatureSpan">argparse.HelpFormatter.prototype.</span>_formatText (text)](#apidoc.element.argparse.HelpFormatter.prototype._formatText)
- description and source-code
```javascript
_formatText = function (text) {
  text = sprintf(text, { prog: this._prog });
  var textWidth = this._width - this._currentIndent;
  var indentIncriment = $$.repeat(' ', this._currentIndent);
  return this._fillText(text, textWidth, indentIncriment) + c.EOL + c.EOL;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.HelpFormatter.prototype._formatUsage"></a>[function <span class="apidocSignatureSpan">argparse.HelpFormatter.prototype.</span>_formatUsage (usage, actions, groups, prefix)](#apidoc.element.argparse.HelpFormatter.prototype._formatUsage)
- description and source-code
```javascript
_formatUsage = function (usage, actions, groups, prefix) {
  if (!prefix && typeof prefix !== 'string') {
    prefix = 'usage: ';
  }

  actions = actions || [];
  groups = groups || [];


  // if usage is specified, use that
  if (usage) {
    usage = sprintf(usage, { prog: this._prog });

    // if no optionals or positionals are available, usage is just prog
  } else if (!usage && actions.length === 0) {
    usage = this._prog;

    // if optionals and positionals are available, calculate usage
  } else if (!usage) {
    var prog = this._prog;
    var optionals = [];
    var positionals = [];
    var actionUsage;
    var textWidth;

    // split optionals from positionals
    actions.forEach(function (action) {
      if (action.isOptional()) {
        optionals.push(action);
      } else {
        positionals.push(action);
      }
    });

    // build full usage string
    actionUsage = this._formatActionsUsage([].concat(optionals, positionals), groups);
    usage = [ prog, actionUsage ].join(' ');

    // wrap the usage parts if it's too long
    textWidth = this._width - this._currentIndent;
    if ((prefix.length + usage.length) > textWidth) {

      // break usage into wrappable parts
      var regexpPart = new RegExp('\\(.*?\\)+|\\[.*?\\]+|\\S+', 'g');
      var optionalUsage = this._formatActionsUsage(optionals, groups);
      var positionalUsage = this._formatActionsUsage(positionals, groups);


      var optionalParts = optionalUsage.match(regexpPart);
      var positionalParts = positionalUsage.match(regexpPart) || [];

      if (optionalParts.join(' ') !== optionalUsage) {
        throw new Error('assert "optionalParts.join(\' \') === optionalUsage"');
      }
      if (positionalParts.join(' ') !== positionalUsage) {
        throw new Error('assert "positionalParts.join(\' \') === positionalUsage"');
      }

      // helper for wrapping lines
      /*eslint-disable func-style*/ // node 0.10 compat
      var _getLines = function (parts, indent, prefix) {
        var lines = [];
        var line = [];

        var lineLength = prefix ? prefix.length - 1 : indent.length - 1;

        parts.forEach(function (part) {
          if (lineLength + 1 + part.length > textWidth) {
            lines.push(indent + line.join(' '));
            line = [];
            lineLength = indent.length - 1;
          }
          line.push(part);
          lineLength += part.length + 1;
        });

        if (line) {
          lines.push(indent + line.join(' '));
        }
        if (prefix) {
          lines[0] = lines[0].substr(indent.length);
        }
        return lines;
      };

      var lines, indent, parts;
      // if prog is short, follow it with optionals or positionals
      if (prefix.length + prog.length <= 0.75 * textWidth) {
        indent = $$.repeat(' ', (prefix.length + prog.length + 1));
        if (optionalParts) {
          lines = [].concat(
            _getLines([ prog ].concat(optionalParts), indent, prefix),
            _getLines(positionalParts, indent)
          );
        } else if (positionalParts) {
          lines = _getLines([ prog ].concat(positionalParts), indent, prefix);
        } else {
          lines = [ prog ];
        }

        // if prog is long, put it on its own line
      } else {
        indent = $$.repeat(' ', prefix.length);
        parts = optionalParts + positionalParts;
        lines = _getLines(parts, indent);
        if (lines.length > 1) {
          lines = [].concat(
            _getLines(optionalParts, indent),
            _getLines(positionalParts, indent)
          );
        }
        lines = [ prog ] + lines;
      }
      // join lines into usage
      usage = lines.join(c.EOL);
    }
  }

  // prefix with 'usage:'
  return prefix + usage + c.EOL + c.EOL;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.HelpFormatter.prototype._getHelpString"></a>[function <span class="apidocSignatureSpan">argparse.HelpFormatter.prototype.</span>_getHelpString (action)](#apidoc.element.argparse.HelpFormatter.prototype._getHelpString)
- description and source-code
```javascript
_getHelpString = function (action) {
  return action.help;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.HelpFormatter.prototype._indent"></a>[function <span class="apidocSignatureSpan">argparse.HelpFormatter.prototype.</span>_indent ()](#apidoc.element.argparse.HelpFormatter.prototype._indent)
- description and source-code
```javascript
_indent = function () {
  this._currentIndent += this._indentIncriment;
  this._level += 1;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.HelpFormatter.prototype._joinParts"></a>[function <span class="apidocSignatureSpan">argparse.HelpFormatter.prototype.</span>_joinParts (partStrings)](#apidoc.element.argparse.HelpFormatter.prototype._joinParts)
- description and source-code
```javascript
_joinParts = function (partStrings) {
  return partStrings.filter(function (part) {
    return (part && part !== c.SUPPRESS);
  }).join('');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.HelpFormatter.prototype._metavarFormatter"></a>[function <span class="apidocSignatureSpan">argparse.HelpFormatter.prototype.</span>_metavarFormatter (action, metavarDefault)](#apidoc.element.argparse.HelpFormatter.prototype._metavarFormatter)
- description and source-code
```javascript
_metavarFormatter = function (action, metavarDefault) {
  var result;

  if (action.metavar || action.metavar === '') {
    result = action.metavar;
  } else if (action.choices) {
    var choices = action.choices;

    if (typeof choices === 'string') {
      choices = choices.split('').join(', ');
    } else if (Array.isArray(choices)) {
      choices = choices.join(',');
    } else {
      choices = Object.keys(choices).join(',');
    }
    result = '{' + choices + '}';
  } else {
    result = metavarDefault;
  }

  return function (size) {
    if (Array.isArray(result)) {
      return result;
    }

    var metavars = [];
    for (var i = 0; i < size; i += 1) {
      metavars.push(result);
    }
    return metavars;
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.HelpFormatter.prototype._splitLines"></a>[function <span class="apidocSignatureSpan">argparse.HelpFormatter.prototype.</span>_splitLines (text, width)](#apidoc.element.argparse.HelpFormatter.prototype._splitLines)
- description and source-code
```javascript
_splitLines = function (text, width) {
  var lines = [];
  var delimiters = [ ' ', '.', ',', '!', '?' ];
  var re = new RegExp('[' + delimiters.join('') + '][^' + delimiters.join('') + ']*$');

  text = text.replace(/[\n\|\t]/g, ' ');

  text = text.trim();
  text = text.replace(this._whitespaceMatcher, ' ');

  // Wraps the single paragraph in text (a string) so every line
  // is at most width characters long.
  text.split(c.EOL).forEach(function (line) {
    if (width >= line.length) {
      lines.push(line);
      return;
    }

    var wrapStart = 0;
    var wrapEnd = width;
    var delimiterIndex = 0;
    while (wrapEnd <= line.length) {
      if (wrapEnd !== line.length && delimiters.indexOf(line[wrapEnd] < -1)) {
        delimiterIndex = (re.exec(line.substring(wrapStart, wrapEnd)) || {}).index;
        wrapEnd = wrapStart + delimiterIndex + 1;
      }
      lines.push(line.substring(wrapStart, wrapEnd));
      wrapStart = wrapEnd;
      wrapEnd += width;
    }
    if (wrapStart < line.length) {
      lines.push(line.substring(wrapStart, wrapEnd));
    }
  });

  return lines;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.HelpFormatter.prototype.addArgument"></a>[function <span class="apidocSignatureSpan">argparse.HelpFormatter.prototype.</span>addArgument (action)](#apidoc.element.argparse.HelpFormatter.prototype.addArgument)
- description and source-code
```javascript
addArgument = function (action) {
  if (action.help !== c.SUPPRESS) {
    var self = this;

    // find all invocations
    var invocations = [ this._formatActionInvocation(action) ];
    var invocationLength = invocations[0].length;

    var actionLength;

    if (action._getSubactions) {
      this._indent();
      action._getSubactions().forEach(function (subaction) {

        var invocationNew = self._formatActionInvocation(subaction);
        invocations.push(invocationNew);
        invocationLength = Math.max(invocationLength, invocationNew.length);

      });
      this._dedent();
    }

    // update the maximum item length
    actionLength = invocationLength + this._currentIndent;
    this._actionMaxLength = Math.max(this._actionMaxLength, actionLength);

    // add the item to the list
    this._addItem(this._formatAction, [ action ]);
  }
}
```
- example usage
```shell
...

var ArgumentParser = require('../lib/argparse').ArgumentParser;
var parser = new ArgumentParser({
version: '0.0.1',
addHelp:true,
description: 'Argparse example'
});
parser.addArgument(
[ '-f', '--foo' ],
{
  help: 'foo bar'
}
);
parser.addArgument(
[ '-b', '--bar' ],
...
```

#### <a name="apidoc.element.argparse.HelpFormatter.prototype.addArguments"></a>[function <span class="apidocSignatureSpan">argparse.HelpFormatter.prototype.</span>addArguments (actions)](#apidoc.element.argparse.HelpFormatter.prototype.addArguments)
- description and source-code
```javascript
addArguments = function (actions) {
  var self = this;
  actions.forEach(function (action) {
    self.addArgument(action);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.HelpFormatter.prototype.addText"></a>[function <span class="apidocSignatureSpan">argparse.HelpFormatter.prototype.</span>addText (text)](#apidoc.element.argparse.HelpFormatter.prototype.addText)
- description and source-code
```javascript
addText = function (text) {
  if (text && text !== c.SUPPRESS) {
    this._addItem(this._formatText, [ text ]);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.HelpFormatter.prototype.addUsage"></a>[function <span class="apidocSignatureSpan">argparse.HelpFormatter.prototype.</span>addUsage (usage, actions, groups, prefix)](#apidoc.element.argparse.HelpFormatter.prototype.addUsage)
- description and source-code
```javascript
addUsage = function (usage, actions, groups, prefix) {
  if (usage !== c.SUPPRESS) {
    this._addItem(this._formatUsage, [ usage, actions, groups, prefix ]);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.HelpFormatter.prototype.endSection"></a>[function <span class="apidocSignatureSpan">argparse.HelpFormatter.prototype.</span>endSection ()](#apidoc.element.argparse.HelpFormatter.prototype.endSection)
- description and source-code
```javascript
endSection = function () {
  this._currentSection = this._currentSection._parent;
  this._dedent();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.HelpFormatter.prototype.formatHelp"></a>[function <span class="apidocSignatureSpan">argparse.HelpFormatter.prototype.</span>formatHelp ()](#apidoc.element.argparse.HelpFormatter.prototype.formatHelp)
- description and source-code
```javascript
formatHelp = function () {
  var help = this._rootSection.formatHelp(this);
  if (help) {
    help = help.replace(this._longBreakMatcher, c.EOL + c.EOL);
    help = $$.trimChars(help, c.EOL) + c.EOL;
  }
  return help;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.HelpFormatter.prototype.startSection"></a>[function <span class="apidocSignatureSpan">argparse.HelpFormatter.prototype.</span>startSection (heading)](#apidoc.element.argparse.HelpFormatter.prototype.startSection)
- description and source-code
```javascript
startSection = function (heading) {
  this._indent();
  var section = new Section(this._currentSection, heading);
  var func = section.formatHelp.bind(section);
  this._addItem(func, [ this ]);
  this._currentSection = section;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.argparse.Namespace"></a>[module argparse.Namespace](#apidoc.module.argparse.Namespace)

#### <a name="apidoc.element.argparse.Namespace.Namespace"></a>[function <span class="apidocSignatureSpan">argparse.</span>Namespace (options)](#apidoc.element.argparse.Namespace.Namespace)
- description and source-code
```javascript
function Namespace(options) {
  $$.extend(this, options);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.argparse.Namespace.prototype"></a>[module argparse.Namespace.prototype](#apidoc.module.argparse.Namespace.prototype)

#### <a name="apidoc.element.argparse.Namespace.prototype.get"></a>[function <span class="apidocSignatureSpan">argparse.Namespace.prototype.</span>get (key, defaultValue)](#apidoc.element.argparse.Namespace.prototype.get)
- description and source-code
```javascript
get = function (key, defaultValue) {
  return !this[key] ? defaultValue : this[key];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.Namespace.prototype.isset"></a>[function <span class="apidocSignatureSpan">argparse.Namespace.prototype.</span>isset (key)](#apidoc.element.argparse.Namespace.prototype.isset)
- description and source-code
```javascript
isset = function (key) {
  return $$.has(this, key);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.Namespace.prototype.set"></a>[function <span class="apidocSignatureSpan">argparse.Namespace.prototype.</span>set (key, value)](#apidoc.element.argparse.Namespace.prototype.set)
- description and source-code
```javascript
set = function (key, value) {
  if (typeof (key) === 'object') {
    $$.extend(this, key);
  } else {
    this[key] = value;
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.Namespace.prototype.unset"></a>[function <span class="apidocSignatureSpan">argparse.Namespace.prototype.</span>unset (key, defaultValue)](#apidoc.element.argparse.Namespace.prototype.unset)
- description and source-code
```javascript
unset = function (key, defaultValue) {
  var value = this[key];
  if (value !== null) {
    delete this[key];
    return value;
  }
  return defaultValue;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.argparse.RawDescriptionHelpFormatter"></a>[module argparse.RawDescriptionHelpFormatter](#apidoc.module.argparse.RawDescriptionHelpFormatter)

#### <a name="apidoc.element.argparse.RawDescriptionHelpFormatter.RawDescriptionHelpFormatter"></a>[function <span class="apidocSignatureSpan">argparse.</span>RawDescriptionHelpFormatter (options)](#apidoc.element.argparse.RawDescriptionHelpFormatter.RawDescriptionHelpFormatter)
- description and source-code
```javascript
function RawDescriptionHelpFormatter(options) {
  HelpFormatter.call(this, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.RawDescriptionHelpFormatter.super_"></a>[function <span class="apidocSignatureSpan">argparse.RawDescriptionHelpFormatter.</span>super_ (options)](#apidoc.element.argparse.RawDescriptionHelpFormatter.super_)
- description and source-code
```javascript
function HelpFormatter(options) {
  options = options || {};

  this._prog = options.prog;

  this._maxHelpPosition = options.maxHelpPosition || 24;
  this._width = (options.width || ((process.env.COLUMNS || 80) - 2));

  this._currentIndent = 0;
  this._indentIncriment = options.indentIncriment || 2;
  this._level = 0;
  this._actionMaxLength = 0;

  this._rootSection = new Section(null);
  this._currentSection = this._rootSection;

  this._whitespaceMatcher = new RegExp('\\s+', 'g');
  this._longBreakMatcher = new RegExp(c.EOL + c.EOL + c.EOL + '+', 'g');
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.argparse.RawDescriptionHelpFormatter.prototype"></a>[module argparse.RawDescriptionHelpFormatter.prototype](#apidoc.module.argparse.RawDescriptionHelpFormatter.prototype)

#### <a name="apidoc.element.argparse.RawDescriptionHelpFormatter.prototype._fillText"></a>[function <span class="apidocSignatureSpan">argparse.RawDescriptionHelpFormatter.prototype.</span>_fillText (text, width, indent)](#apidoc.element.argparse.RawDescriptionHelpFormatter.prototype._fillText)
- description and source-code
```javascript
_fillText = function (text, width, indent) {
  var lines = text.split('\n');
  lines = lines.map(function (line) {
    return $$.trimEnd(indent + line);
  });
  return lines.join('\n');
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.argparse.RawTextHelpFormatter"></a>[module argparse.RawTextHelpFormatter](#apidoc.module.argparse.RawTextHelpFormatter)

#### <a name="apidoc.element.argparse.RawTextHelpFormatter.RawTextHelpFormatter"></a>[function <span class="apidocSignatureSpan">argparse.</span>RawTextHelpFormatter (options)](#apidoc.element.argparse.RawTextHelpFormatter.RawTextHelpFormatter)
- description and source-code
```javascript
function RawTextHelpFormatter(options) {
  RawDescriptionHelpFormatter.call(this, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.RawTextHelpFormatter.super_"></a>[function <span class="apidocSignatureSpan">argparse.RawTextHelpFormatter.</span>super_ (options)](#apidoc.element.argparse.RawTextHelpFormatter.super_)
- description and source-code
```javascript
function RawDescriptionHelpFormatter(options) {
  HelpFormatter.call(this, options);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.argparse.RawTextHelpFormatter.prototype"></a>[module argparse.RawTextHelpFormatter.prototype](#apidoc.module.argparse.RawTextHelpFormatter.prototype)

#### <a name="apidoc.element.argparse.RawTextHelpFormatter.prototype._splitLines"></a>[function <span class="apidocSignatureSpan">argparse.RawTextHelpFormatter.prototype.</span>_splitLines (text)](#apidoc.element.argparse.RawTextHelpFormatter.prototype._splitLines)
- description and source-code
```javascript
_splitLines = function (text) {
  return text.split('\n');
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.argparse.utils"></a>[module argparse.utils](#apidoc.module.argparse.utils)

#### <a name="apidoc.element.argparse.utils.arrayEqual"></a>[function <span class="apidocSignatureSpan">argparse.utils.</span>arrayEqual (a, b)](#apidoc.element.argparse.utils.arrayEqual)
- description and source-code
```javascript
arrayEqual = function (a, b) {
  if (a.length !== b.length) { return false; }
  for (var i = 0; i < a.length; i++) {
    if (a[i] !== b[i]) { return false; }
  }
  return true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.utils.arrayUnion"></a>[function <span class="apidocSignatureSpan">argparse.utils.</span>arrayUnion ()](#apidoc.element.argparse.utils.arrayUnion)
- description and source-code
```javascript
arrayUnion = function () {
  var result = [];
  for (var i = 0, values = {}; i < arguments.length; i++) {
    var arr = arguments[i];
    for (var j = 0; j < arr.length; j++) {
      if (!values[arr[j]]) {
        values[arr[j]] = true;
        result.push(arr[j]);
      }
    }
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.utils.capitalize"></a>[function <span class="apidocSignatureSpan">argparse.utils.</span>capitalize (str)](#apidoc.element.argparse.utils.capitalize)
- description and source-code
```javascript
capitalize = function (str) {
  return str.charAt(0).toUpperCase() + str.slice(1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.utils.extend"></a>[function <span class="apidocSignatureSpan">argparse.utils.</span>extend (dest, src)](#apidoc.element.argparse.utils.extend)
- description and source-code
```javascript
extend = function (dest, src) {
  for (var i in src) {
    if (has(src, i)) { dest[i] = src[i]; }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.utils.has"></a>[function <span class="apidocSignatureSpan">argparse.utils.</span>has (obj, key)](#apidoc.element.argparse.utils.has)
- description and source-code
```javascript
function has(obj, key) {
  return Object.prototype.hasOwnProperty.call(obj, key);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.utils.repeat"></a>[function <span class="apidocSignatureSpan">argparse.utils.</span>repeat (str, num)](#apidoc.element.argparse.utils.repeat)
- description and source-code
```javascript
repeat = function (str, num) {
  var result = '';
  for (var i = 0; i < num; i++) { result += str; }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.utils.trimChars"></a>[function <span class="apidocSignatureSpan">argparse.utils.</span>trimChars (str, chars)](#apidoc.element.argparse.utils.trimChars)
- description and source-code
```javascript
trimChars = function (str, chars) {
  var start = 0;
  var end = str.length - 1;
  while (chars.indexOf(str.charAt(start)) >= 0) { start++; }
  while (chars.indexOf(str.charAt(end)) >= 0) { end--; }
  return str.slice(start, end + 1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.argparse.utils.trimEnd"></a>[function <span class="apidocSignatureSpan">argparse.utils.</span>trimEnd (str)](#apidoc.element.argparse.utils.trimEnd)
- description and source-code
```javascript
trimEnd = function (str) {
  return str.replace(/\s+$/g, '');
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
