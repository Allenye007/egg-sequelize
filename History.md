
2.1.5 / 2018-07-03
==================

**others**
  * [[`921536f`](http://github.com/eggjs/egg-sequelize/commit/921536f20578c213dfe6c4d0c09418c169a7c8dc)] - Retry 3 times on startup when database connect fail in temporary, to avoid Egg start failed. (#56) (Jason Lee <<huacnlee@gmail.com>>)

2.1.4 / 2017-05-11
==================

  * fix(migration): always use production config (#14)

2.1.3 / 2017-05-11
==================

  * fix: Migration load config.seuqelize for function type config support.

2.1.2 / 2017-05-11
==================

  * fix: egg-sequelize bin to find correct sequelize-cli path in node_modules.

2.1.1 / 2017-05-10
==================

  * feat: add `egg-sequelize` bin for Sequelize migrations support. (#11)

2.0.2 / 2017-04-27
==================

  * fix: ignore non Sequelize files in app/model path for Model loader. (#10)
  * docs: add Suggestions and License (#8)
  * feat: use underscore style column name as default (#7)
  * docs: add info about how to enable sequelize plugin (#6)

2.0.1 / 2017-03-14
==================

  * fix: Allow all of Sequelize options in `config.sequelize` (#5)

2.0.0 / 2017-03-13
==================

  * feat: [BREAKING_CHANGE] Update default Sequelize configs (#4)

1.0.0 / 2017-02-19
==================

  * chore: complete unittest (#2)
  * feat: use loader API to load models (#3)

