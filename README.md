PS C:\xampp\htdocs\SICAP\desafio2\KumbiaPHP> echo "# Desafio_2" >> README.md
>> git init
>> git add README.md
>> git commit -m "first commit"
>> git branch -M main
>> git remote add origin https://github.com/elisagzavala/Desafio_2.git
>> git push -u origin main
Initialized empty Git repository in C:/xampp/htdocs/SICAP/desafio2/KumbiaPHP/.git/
[master (root-commit) f22f1e9] first commit
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 README.md
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 341 bytes | 170.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/elisagzavala/Desafio_2.git
 * [new branch]      main -> main
Branch 'main' set up to track remote branch 'main' from 'origin'.
PS C:\xampp\htdocs\SICAP\desafio2\KumbiaPHP> git push
Everything up-to-date
PS C:\xampp\htdocs\SICAP\desafio2\KumbiaPHP> git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .codeclimate.yml
        .htaccess
        .phpmd.xml
        .travis.yml
        LICENSE
        README.EN.md
        composer.json
        core/
        default/
        vendor/

nothing added to commit but untracked files present (use "git add" to track)
PS C:\xampp\htdocs\SICAP\desafio2\KumbiaPHP> git add .
warning: LF will be replaced by CRLF in default/app/controllers/ciudades_controller.php.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in default/app/controllers/cuentas_controller.php.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in default/app/controllers/empleados_controller.php.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in default/app/controllers/estados_controller.php.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in default/app/controllers/sucursales_controller.php.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in default/app/controllers/tarjetas_controller.php.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in default/app/controllers/usuarios_controller.php.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in default/app/models/ciudades.php.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in default/app/models/cuentas.php.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in default/app/models/empleados.php.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in default/app/models/estados.php.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in default/app/models/sucursales.php.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in default/app/models/tarjetas.php.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in default/app/models/usuarios.php.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in default/app/models/utils.php.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in default/app/views/_shared/partials/desafios/desafio1/form_builder.phtml.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in default/app/views/_shared/partials/desafios/desafio1/list_builder.phtml.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in default/app/views/_shared/templates/desafios/desafio1.phtml.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in default/app/views/ciudades/crear.phtml.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in default/app/views/ciudades/editar.phtml.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in default/app/views/ciudades/index.phtml.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in default/app/views/ciudades/listar.phtml.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in default/app/views/cuentas/crear.phtml.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in default/app/views/cuentas/editar.phtml.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in default/app/views/cuentas/index.phtml.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in default/app/views/cuentas/listar.phtml.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in default/app/views/empleados/crear.phtml.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in default/app/views/empleados/editar.phtml.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in default/app/views/empleados/index.phtml.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in default/app/views/empleados/listar.phtml.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in default/app/views/estados/crear.phtml.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in default/app/views/estados/editar.phtml.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in default/app/views/estados/index.phtml.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in default/app/views/estados/listar.phtml.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in default/app/views/sucursales/crear.phtml.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in default/app/views/sucursales/editar.phtml.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in default/app/views/sucursales/index.phtml.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in default/app/views/sucursales/listar.phtml.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in default/app/views/tarjetas/crear.phtml.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in default/app/views/tarjetas/editar.phtml.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in default/app/views/tarjetas/index.phtml.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in default/app/views/tarjetas/listar.phtml.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in default/app/views/usuarios/crear.phtml.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in default/app/views/usuarios/editar.phtml.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in default/app/views/usuarios/index.phtml.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in default/app/views/usuarios/listar.phtml.
The file will have its original line endings in your working directory
PS C:\xampp\htdocs\SICAP\desafio2\KumbiaPHP> git commit -m "lo que sea"
[main ea1eb28] lo que sea
 273 files changed, 24998 insertions(+)
 create mode 100644 .codeclimate.yml
 create mode 100644 .htaccess
 create mode 100644 .phpmd.xml
 create mode 100644 .travis.yml
 create mode 100644 LICENSE
 create mode 100644 README.EN.md
 create mode 100644 composer.json
 create mode 100644 core/.htaccess
 create mode 100644 core/console/cache_console.php
 create mode 100644 core/console/controller_console.php
 create mode 100644 core/console/generators/controller.php
 create mode 100644 core/console/generators/model.php
 create mode 100644 core/console/kumbia.php
 create mode 100644 core/console/model_console.php
 create mode 100644 core/extensions/helpers/ajax.php
 create mode 100644 core/extensions/helpers/css.php
 create mode 100644 core/extensions/helpers/flash.php
 create mode 100644 core/extensions/helpers/form.php
 create mode 100644 core/extensions/helpers/html.php
 create mode 100644 core/extensions/helpers/js.php
 create mode 100644 core/extensions/helpers/model_form.php
 create mode 100644 core/extensions/helpers/tag.php
 create mode 100644 core/extensions/scaffolds/empty
 create mode 100644 core/kumbia/autoload.php
 create mode 100644 core/kumbia/bootstrap.php
 create mode 100644 core/kumbia/config.php
 create mode 100644 core/kumbia/console.php
 create mode 100644 core/kumbia/controller.php
 create mode 100644 core/kumbia/kumbia_exception.php
 create mode 100644 core/kumbia/kumbia_facade.php
 create mode 100644 core/kumbia/kumbia_rest.php
 create mode 100644 core/kumbia/kumbia_router.php
 create mode 100644 core/kumbia/kumbia_version.php
 create mode 100644 core/kumbia/kumbia_view.php
 create mode 100644 core/kumbia/load.php
 create mode 100644 core/kumbia/router.php
 create mode 100644 core/kumbia/util.php
 create mode 100644 core/kumbia/workerboot.php
 create mode 100644 core/libs/acl/acl.php
 create mode 100644 core/libs/acl/resource/resource.php
 create mode 100644 core/libs/acl/role/role.php
 create mode 100644 core/libs/acl2/acl2.php
 create mode 100644 core/libs/acl2/adapters/simple_acl.php
 create mode 100644 core/libs/auth/adapters/digest_auth.php
 create mode 100644 core/libs/auth/adapters/kerberos5_auth.php
 create mode 100644 core/libs/auth/adapters/model_auth.php
 create mode 100644 core/libs/auth/adapters/radius_auth.php
 create mode 100644 core/libs/auth/auth.php
 create mode 100644 core/libs/auth/auth_interface.php
 create mode 100644 core/libs/auth2/adapters/model_auth.php
 create mode 100644 core/libs/auth2/auth2.php
 create mode 100644 core/libs/benchmark/benchmark.php
 create mode 100644 core/libs/cache/cache.php
 create mode 100644 core/libs/cache/drivers/APC_cache.php
 create mode 100644 core/libs/cache/drivers/file_cache.php
 create mode 100644 core/libs/cache/drivers/nixfile_cache.php
 create mode 100644 core/libs/cache/drivers/sqlite_cache.php
 create mode 100644 core/libs/date/date.php
 create mode 100644 core/libs/db/adapters/firebird.php
 create mode 100644 core/libs/db/adapters/informix.php
 create mode 100644 core/libs/db/adapters/mssql.php
 create mode 100644 core/libs/db/adapters/mysql.php
 create mode 100644 core/libs/db/adapters/oracle.php
 create mode 100644 core/libs/db/adapters/pdo.php
 create mode 100644 core/libs/db/adapters/pdo/access.php
 create mode 100644 core/libs/db/adapters/pdo/informix.php
 create mode 100644 core/libs/db/adapters/pdo/interface.php
 create mode 100644 core/libs/db/adapters/pdo/mssql.php
 create mode 100644 core/libs/db/adapters/pdo/mysql.php
 create mode 100644 core/libs/db/adapters/pdo/oracle.php
 create mode 100644 core/libs/db/adapters/pdo/pgsql.php
 create mode 100644 core/libs/db/adapters/pdo/sqlite.php
 create mode 100644 core/libs/db/adapters/pgsql.php
 create mode 100644 core/libs/db/adapters/sqlite.php
 create mode 100644 core/libs/db/db.php
 create mode 100644 core/libs/db/db_base.php
 create mode 100644 core/libs/db/db_base_interface.php
 create mode 100644 core/libs/event/event.php
 create mode 100644 core/libs/event/hook.php
 create mode 100644 core/libs/file_util/file_util.php
 create mode 100644 core/libs/filter/base_filter/addslashes_filter.php
 create mode 100644 core/libs/filter/base_filter/alnum_filter.php
 create mode 100644 core/libs/filter/base_filter/alpha_filter.php
 create mode 100644 core/libs/filter/base_filter/date_filter.php
 create mode 100644 core/libs/filter/base_filter/digits_filter.php
 create mode 100644 core/libs/filter/base_filter/htmlentities_filter.php
 create mode 100644 core/libs/filter/base_filter/htmlspecialchars_filter.php
 create mode 100644 core/libs/filter/base_filter/int_filter.php
 create mode 100644 core/libs/filter/base_filter/ipv4_filter.php
 create mode 100644 core/libs/filter/base_filter/lower_filter.php
 create mode 100644 core/libs/filter/base_filter/md5_filter.php
 create mode 100644 core/libs/filter/base_filter/nl2br_filter.php
 create mode 100644 core/libs/filter/base_filter/numeric_filter.php
 create mode 100644 core/libs/filter/base_filter/stripslashes_filter.php
 create mode 100644 core/libs/filter/base_filter/stripspace_filter.php
 create mode 100644 core/libs/filter/base_filter/striptags_filter.php
 create mode 100644 core/libs/filter/base_filter/trim_filter.php
 create mode 100644 core/libs/filter/base_filter/upper_filter.php
 create mode 100644 core/libs/filter/filter.php
 create mode 100644 core/libs/filter/filter_interface.php
 create mode 100644 core/libs/i18n/i18n.php
 create mode 100644 core/libs/input/input.php
 create mode 100644 core/libs/kumbia_active_record/behaviors/paginate.php
 create mode 100644 core/libs/kumbia_active_record/kumbia_active_record.php
 create mode 100644 core/libs/kumbia_auth/kumbia_auth.php
 create mode 100644 core/libs/kumbia_auth_base/kumbia_auth_base.php
 create mode 100644 core/libs/logger/logger.php
 create mode 100644 core/libs/redirect/redirect.php
 create mode 100644 core/libs/registry/registry.php
 create mode 100644 core/libs/rest/rest.php
 create mode 100644 core/libs/security/security.php
 create mode 100644 core/libs/session/session.php
 create mode 100644 core/libs/upload/adapters/file_upload.php
 create mode 100644 core/libs/upload/adapters/image_upload.php
 create mode 100644 core/libs/upload/upload.php
 create mode 100644 core/libs/validate/validate.php
 create mode 100644 core/libs/validate/validations.php
 create mode 100644 core/phpunit.xml.dist
 create mode 100644 core/tests/bootstrap.php
 create mode 100644 core/tests/classes/extensions/helpers/FlashTest.php
 create mode 100644 core/tests/classes/extensions/helpers/HtmlTest.php
 create mode 100644 core/tests/classes/extensions/helpers/TagTest.php
 create mode 100644 core/tests/classes/kumbia/UtilTest.php
 create mode 100644 core/tests/classes/libs/input/InputTest.php
 create mode 100644 core/tests/classes/libs/session/SessionTest.php
 create mode 100644 core/views/errors/exception.phtml
 create mode 100644 core/views/errors/no_action.phtml
 create mode 100644 core/views/errors/no_controller.phtml
 create mode 100644 core/views/errors/no_model.phtml
 create mode 100644 core/views/errors/no_partial.phtml
 create mode 100644 core/views/errors/no_view.phtml
 create mode 100644 core/views/errors/num_params.phtml
 create mode 100644 core/views/partials/kumbia/empty
 create mode 100644 core/views/partials/paginators/classic.phtml
 create mode 100644 core/views/partials/paginators/digg.phtml
 create mode 100644 core/views/partials/paginators/extended.phtml
 create mode 100644 core/views/partials/paginators/punbb.phtml
 create mode 100644 core/views/partials/paginators/simple.phtml
 create mode 100644 core/views/templates/default.phtml
 create mode 100644 core/views/templates/error.phtml
 create mode 100644 core/views/templates/exception.phtml
 create mode 100644 default/.htaccess
 create mode 100644 default/app/.htaccess
 create mode 100644 default/app/bin/metrics
 create mode 100644 default/app/bin/phpserver
 create mode 100644 default/app/config/config.php
 create mode 100644 default/app/config/databases.php
 create mode 100644 default/app/config/routes.php
 create mode 100644 default/app/controllers/ciudades_controller.php
 create mode 100644 default/app/controllers/cuentas_controller.php
 create mode 100644 default/app/controllers/empleados_controller.php
 create mode 100644 default/app/controllers/estados_controller.php
 create mode 100644 default/app/controllers/index_controller.php
 create mode 100644 default/app/controllers/login_controller.php
 create mode 100644 default/app/controllers/pages_controller.php
 create mode 100644 default/app/controllers/rest_controller.php
 create mode 100644 default/app/controllers/sucursales_controller.php
 create mode 100644 default/app/controllers/tarjetas_controller.php
 create mode 100644 default/app/controllers/usuarios_controller.php
 create mode 100644 default/app/extensions/console/empty
 create mode 100644 default/app/extensions/filters/empty
 create mode 100644 default/app/extensions/helpers/empty
 create mode 100644 default/app/extensions/scaffolds/empty
 create mode 100644 default/app/libs/active_record.php
 create mode 100644 default/app/libs/admin_controller.php
 create mode 100644 default/app/libs/app_controller.php
 create mode 100644 default/app/libs/bootstrap.php
 create mode 100644 default/app/libs/rest_controller.php
 create mode 100644 default/app/libs/scaffold_controller.php
 create mode 100644 default/app/libs/view.php
 create mode 100644 default/app/locale/es_ES/LC_MESSAGES/default.mo
 create mode 100644 default/app/locale/es_ES/LC_MESSAGES/default.po
 create mode 100644 default/app/models/ciudades.php
 create mode 100644 default/app/models/cuentas.php
 create mode 100644 default/app/models/empleados.php
 create mode 100644 default/app/models/empty
 create mode 100644 default/app/models/estados.php
 create mode 100644 default/app/models/sucursales.php
 create mode 100644 default/app/models/tarjetas.php
 create mode 100644 default/app/models/usuarios.php
 create mode 100644 default/app/models/utils.php
 create mode 100644 default/app/phpunit.xml.dist
 create mode 100644 default/app/temp/cache/empty
 create mode 100644 default/app/temp/logs/empty
 create mode 100644 default/app/tests/Controller/PagesControllerTest.php
 create mode 100644 default/app/tests/KumbiaTestTrait.php
 create mode 100644 default/app/tests/bootstrap.php
 create mode 100644 default/app/views/_shared/errors/404.phtml
 create mode 100644 default/app/views/_shared/partials/desafios/desafio1/form_builder.phtml
 create mode 100644 default/app/views/_shared/partials/desafios/desafio1/list_builder.phtml
 create mode 100644 default/app/views/_shared/partials/kumbia/footer.phtml
 create mode 100644 default/app/views/_shared/scaffolds/kumbia/crear.phtml
 create mode 100644 default/app/views/_shared/scaffolds/kumbia/index.phtml
 create mode 100644 default/app/views/_shared/scaffolds/kumbia/ver.phtml
 create mode 100644 default/app/views/_shared/templates/csv.phtml
 create mode 100644 default/app/views/_shared/templates/default.phtml
 create mode 100644 default/app/views/_shared/templates/desafios/desafio1.phtml
 create mode 100644 default/app/views/_shared/templates/json.phtml
 create mode 100644 default/app/views/_shared/templates/xml.phtml
 create mode 100644 default/app/views/ciudades/crear.phtml
 create mode 100644 default/app/views/ciudades/detalles.phtml
 create mode 100644 default/app/views/ciudades/editar.phtml
 create mode 100644 default/app/views/ciudades/index.phtml
 create mode 100644 default/app/views/ciudades/listar.phtml
 create mode 100644 default/app/views/cuentas/crear.phtml
 create mode 100644 default/app/views/cuentas/detalles.phtml
 create mode 100644 default/app/views/cuentas/editar.phtml
 create mode 100644 default/app/views/cuentas/index.phtml
 create mode 100644 default/app/views/cuentas/listar.phtml
 create mode 100644 default/app/views/empleados/crear.phtml
 create mode 100644 default/app/views/empleados/detalles.phtml
 create mode 100644 default/app/views/empleados/editar.phtml
 create mode 100644 default/app/views/empleados/index.phtml
 create mode 100644 default/app/views/empleados/listar.phtml
 create mode 100644 default/app/views/estados/crear.phtml
 create mode 100644 default/app/views/estados/detalles.phtml
 create mode 100644 default/app/views/estados/editar.phtml
 create mode 100644 default/app/views/estados/index.phtml
 create mode 100644 default/app/views/estados/listar.phtml
 create mode 100644 default/app/views/index/index.phtml
 create mode 100644 default/app/views/login/index.phtml
 create mode 100644 default/app/views/pages/kumbia/status.phtml
 create mode 100644 default/app/views/sucursales/crear.phtml
 create mode 100644 default/app/views/sucursales/detalles.phtml
 create mode 100644 default/app/views/sucursales/editar.phtml
 create mode 100644 default/app/views/sucursales/index.phtml
 create mode 100644 default/app/views/sucursales/listar.phtml
 create mode 100644 default/app/views/tarjetas/crear.phtml
 create mode 100644 default/app/views/tarjetas/detalles.phtml
 create mode 100644 default/app/views/tarjetas/editar.phtml
 create mode 100644 default/app/views/tarjetas/index.phtml
 create mode 100644 default/app/views/tarjetas/listar.phtml
 create mode 100644 default/app/views/usuarios/crear.phtml
 create mode 100644 default/app/views/usuarios/detalles.phtml
 create mode 100644 default/app/views/usuarios/editar.phtml
 create mode 100644 default/app/views/usuarios/index.phtml
 create mode 100644 default/app/views/usuarios/listar.phtml
 create mode 100644 default/index.php
 create mode 100644 default/public/.htaccess
 create mode 100644 default/public/.user.ini
 create mode 100644 default/public/css/index.html
 create mode 100644 default/public/css/kumbia.css
 create mode 100644 default/public/css/pickadate.css
 create mode 100644 default/public/favicon.ico
 create mode 100644 default/public/files/index.html
 create mode 100644 default/public/files/upload/index.html
 create mode 100644 default/public/img/datepicker/backstripes.gif
 create mode 100644 default/public/img/datepicker/bg_header.jpg
 create mode 100644 default/public/img/datepicker/bullet1.gif
 create mode 100644 default/public/img/datepicker/bullet2.gif
 create mode 100644 default/public/img/datepicker/cal-grey.gif
 create mode 100644 default/public/img/datepicker/cal.gif
 create mode 100644 default/public/img/datepicker/gradient-e5e5e5-ffffff.gif
 create mode 100644 default/public/img/index.html
 create mode 100644 default/public/img/kumbia.svg
 create mode 100644 default/public/img/kumbiaphp.svg
 create mode 100644 default/public/img/logo.png
 create mode 100644 default/public/img/php7.svg
 create mode 100644 default/public/img/upload/index.html
 create mode 100644 default/public/index.html
 create mode 100644 default/public/index.php
 create mode 100644 default/public/javascript/index.html
 create mode 100644 default/public/javascript/jquery/jquery+kumbiaphp.min.js
 create mode 100644 default/public/javascript/jquery/jquery.kumbiaphp.js
 create mode 100644 default/public/javascript/jquery/jquery.kumbiaphp.min.js
 create mode 100644 default/public/javascript/jquery/jquery.min.js
 create mode 100644 default/public/javascript/jquery/pickadate.js
 create mode 100644 default/public/robots.txt
 create mode 100644 default/public/temp/index.html
 create mode 100644 default/public/web.config
 create mode 100644 vendor/.gitkeep
 create mode 100644 vendor/.htaccess
 create mode 100644 vendor/.only-PSR0-libs
PS C:\xampp\htdocs\SICAP\desafio2\KumbiaPHP> git push -u origin master
error: src refspec master does not match any
error: failed to push some refs to 'https://github.com/elisagzavala/Desafio_2.git'
PS C:\xampp\htdocs\SICAP\desafio2\KumbiaPHP> git push -u origin main
Enumerating objects: 322, done.
Counting objects: 100% (322/322), done.
Delta compression using up to 4 threads
Compressing objects: 100% (283/283), done.
Writing objects: 100% (321/321), 259.89 KiB | 2.00 MiB/s, done.
Total 321 (delta 64), reused 0 (delta 0)
remote: Resolving deltas: 100% (64/64), done.
To https://github.com/elisagzavala/Desafio_2.git
   f22f1e9..ea1eb28  main -> main
Branch 'main' set up to track remote branch 'main' from 'origin'.
PS C:\xampp\htdocs\SICAP\desafio2\KumbiaPHP>
#   D e s a f i o _ 3  
 