sa-doxygen
==========

[![Build Status](https://travis-ci.org/softasap/sa-doxygen.svg?branch=master)](https://travis-ci.org/softasap/sa-doxygen)


Installs useful documentation generator for multiple languages [Doxygen](http://www.doxygen.nl)

Example of usage (all parameters are optional)

Simple

```
  roles:
    - {
        role: "sa-doxygen"
      }
```

Advanced:

```
  roles:
    - {
        role: "sa-doxygen"
      }
```


Usage with ansible galaxy workflow
----------------------------------

If you installed the sa-doxygen role using the command


`
   ansible-galaxy install softasap.sa-doxygen
`

the role will be available in the folder library/softasap.sa-doxygen
Please adjust the path accordingly.

```YAML

     - {
         role: "softasap.sa-doxygen"
       }

```

requirements.yml snippet: 

```YAML
- src: softasap.sa-doxygen
  name: sa-doxygen
```




Copyright and license
---------------------

Code is dual licensed under the [BSD 3 clause] (https://opensource.org/licenses/BSD-3-Clause) and the [MIT License] (http://opensource.org/licenses/MIT). Choose the one that suits you best.

Reach us:

Subscribe for roles updates at [FB] (https://www.facebook.com/SoftAsap/)

Join gitter discussion channel at [Gitter](https://gitter.im/softasap)

Discover other roles at  http://www.softasap.com/roles/registry_generated.html

visit our blog at http://www.softasap.com/blog/archive.html


