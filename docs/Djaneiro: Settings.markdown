### Settings

|abbreviation|template|
|:--|:--|
|sabsolute_url_overrides|<pre>ABSOLUTE_URL_OVERRIDES = $VAR1$ $END$</pre>|
|sadmins|<pre>ADMINS = [('$VAR1$', '$VAR2$'), ]$END$</pre>|
|sallowed_hosts|<pre>ALLOWED_HOSTS = $VAR1$ $END$</pre>|
|sappend_slash|<pre>APPEND_SLASH = $VAR1$ $END$</pre>|
|sauth_password_validators|<pre>AUTH_PASSWORD_VALIDATORS = $VAR1$ $END$</pre>|
|sauth_user_model|<pre>AUTH_USER_MODEL = '$VAR1$' $END$</pre>|
|sauthentication_backends|<pre>AUTHENTICATION_BACKENDS = $VAR1$ $END$</pre>|
|scache_middleware_alias|<pre>CACHE_MIDDLEWARE_ALIAS = '$VAR1$' $END$</pre>|
|scache_middleware_key_prefix|<pre>CACHE_MIDDLEWARE_KEY_PREFIX = '$VAR1$' $END$</pre>|
|scache_middleware_seconds|<pre>CACHE_MIDDLEWARE_SECONDS = $VAR1$ $END$</pre>|
|scaches|<pre><br>CACHES = {<br>    '$VAR1$': {<br>        'BACKEND': 'django.core.cache.backends.$VAR2$',<br>        'KEY_FUNCTION': $VAR3$,<br>        'KEY_PREFIX': '$VAR4$',<br>        'LOCATION': '$VAR5$',<br>        'OPTIONS': $VAR6$,<br>        'TIMEOUT': $VAR7$,<br>        'VERSION': $VAR8$<br>    },<br>    $VAR9$<br>}<br>$END$</pre>|
|scsrf_cookie_age|<pre>CSRF_COOKIE_AGE = $VAR1$ $END$</pre>|
|scsrf_cookie_domain|<pre>CSRF_COOKIE_DOMAIN = $VAR1$ $END$</pre>|
|scsrf_cookie_httponly|<pre>CSRF_COOKIE_HTTPONLY = $VAR1$ $END$</pre>|
|scsrf_cookie_name|<pre>CSRF_COOKIE_NAME = '$VAR1$' $END$</pre>|
|scsrf_cookie_path|<pre>CSRF_COOKIE_PATH = '$VAR1$' $END$</pre>|
|scsrf_cookie_secure|<pre>CSRF_COOKIE_SECURE = $VAR1$ $END$</pre>|
|scsrf_failure_view|<pre>CSRF_FAILURE_VIEW = '$VAR1$' $END$</pre>|
|scsrf_header_name|<pre>CSRF_HEADER_NAME = '$VAR1$' $END$</pre>|
|scsrf_trusted_origins|<pre>CSRF_TRUSTED_ORIGINS = $VAR1$ $END$</pre>|
|sdata_upload_max_memory_size|<pre>DATA_UPLOAD_MAX_MEMORY_SIZE = $VAR1$ $END$</pre>|
|sdata_upload_max_number_fields|<pre>DATA_UPLOAD_MAX_NUMBER_FIELDS = $VAR1$ $END$</pre>|
|sdatabase|<pre>'$DBNAME$': {<br>    'ENGINE': 'django.db.backends.$VAR2$',<br>    'NAME': '$VAR3$',<br>    'USER': '$VAR4$',<br>    'PASSWORD': '$VAR5$',<br>    'HOST': '$VAR6$',<br>    'PORT': '$VAR7$',<br>    'ATOMIC_REQUESTS': $VAR8$,<br>    'AUTOCOMMIT': $VAR9$,<br>    'CONN_MAX_AGE': $VAR10$,<br>    'OPTIONS': $VAR11$,<br>    'TIME_ZONE': $VAR12$,<br>    'TEST': {<br>        'NAME': 'test_$DBNAME$',<br>        'CHARSET': $VAR14$,<br>        'COLLATION': $VAR15$,<br>        'DEPENDENCIES': ['$DBNAME$', $VAR17$],<br>        'MIRROR': $VAR18$,<br>        'SERIALIZE': $VAR19$,<br>    },<br>}</pre>|
|sdatabase_routers|<pre>DATABASE_ROUTERS = $VAR1$ $END$</pre>|
|sdatabases|<pre>DATABASES = {<br>    '$DBNAME$': {<br>        'ENGINE': 'django.db.backends.$VAR2$',<br>        'NAME': '$VAR3$',<br>        'USER': '$VAR4$',<br>        'PASSWORD': '$VAR5$',<br>        'HOST': '$VAR6$',<br>        'PORT': '$VAR7$',<br>        'ATOMIC_REQUESTS': $VAR8$,<br>        'AUTOCOMMIT': $VAR9$,<br>        'CONN_MAX_AGE': $VAR10$,<br>        'OPTIONS': $VAR11$,<br>        'TIME_ZONE': $VAR12$,<br>        'TEST': {<br>            'NAME': 'test_$DBNAME$',<br>            'CHARSET': $VAR14$,<br>            'COLLATION': $VAR15$,<br>            'DEPENDENCIES': ['$DBNAME$', $VAR17$],<br>            'MIRROR': $VAR18$,<br>            'SERIALIZE': $VAR19$,<br>        },<br>    }<br>}<br>$END$</pre>|
|sdatabasetest|<pre>'TEST': {<br>    'NAME': $VAR1$,<br>    'CHARSET': $VAR2$,<br>    'COLLATION': $VAR3$,<br>    'DEPENDENCIES': [$VAR4$],<br>    'MIRROR': $VAR5$,<br>    'SERIALIZE': $VAR6$,<br>}</pre>|
|sdate_format|<pre>DATE_FORMAT = '$VAR1$' $END$</pre>|
|sdate_input_formats|<pre>DATE_INPUT_FORMATS = [<br>    '%Y-%m-%d', '%m/%d/%Y', '%m/%d/%y',<br>    '%b %d %Y', '%b %d, %Y',<br>    '%d %b %Y', '%d %b, %Y',<br>    '%B %d %Y', '%B %d, %Y',<br>    '%d %B %Y', '%d %B, %Y',<br>    '$VAR1$'<br>]<br>$end$</pre>|
|sdatetime_format|<pre>DATETIME_FORMAT = '$VAR1$' $END$</pre>|
|sdatetime_input_formats|<pre>DATETIME_INPUT_FORMATS = [<br>    '%Y-%m-%d %H:%M:%S',     # '2006-10-25 14:30:59'<br>    '%Y-%m-%d %H:%M:%S.%f',  # '2006-10-25 14:30:59.000200'<br>    '%Y-%m-%d %H:%M',        # '2006-10-25 14:30'<br>    '%Y-%m-%d',              # '2006-10-25'<br>    '%m/%d/%Y %H:%M:%S',     # '10/25/2006 14:30:59'<br>    '%m/%d/%Y %H:%M:%S.%f',  # '10/25/2006 14:30:59.000200'<br>    '%m/%d/%Y %H:%M',        # '10/25/2006 14:30'<br>    '%m/%d/%Y',              # '10/25/2006'<br>    '%m/%d/%y %H:%M:%S',     # '10/25/06 14:30:59'<br>    '%m/%d/%y %H:%M:%S.%f',  # '10/25/06 14:30:59.000200'<br>    '%m/%d/%y %H:%M',        # '10/25/06 14:30'<br>    '%m/%d/%y',              # '10/25/06'<br>]<br>$END$</pre>|
|sdebug|<pre>DEBUG = $VAR1$ $END$</pre>|
|sdebug_propagate_exceptions|<pre>DEBUG_PROPAGATE_EXCEPTIONS = $VAR1$ $END$</pre>|
|sdecimal_separator|<pre>DECIMAL_SEPARATOR = '$VAR1$' $END$</pre>|
|sdefault_charset|<pre>DEFAULT_CHARSET = '$VAR1$' $END$</pre>|
|sdefault_content_type|<pre>DEFAULT_CONTENT_TYPE = '$VAR1$' $END$</pre>|
|sdefault_exception_reporter_filter|<pre>DEFAULT_EXCEPTION_REPORTER_FILTER = '$VAR1$' $END$</pre>|
|sdefault_file_storage|<pre>DEFAULT_FILE_STORAGE = '$VAR1$' $END$</pre>|
|sdefault_from_email|<pre>DEFAULT_FROM_EMAIL = '$VAR1$' $END$</pre>|
|sdefault_index_tablespace|<pre>DEFAULT_INDEX_TABLESPACE = '$VAR1$' $END$</pre>|
|sdefault_tablespace|<pre>DEFAULT_TABLESPACE = '$VAR1$' $END$</pre>|
|sdisallowed_user_agents|<pre>DISALLOWED_USER_AGENTS = $VAR1$ $END$</pre>|
|semail_backend|<pre>EMAIL_BACKEND = '$VAR1$' $END$</pre>|
|semail_host|<pre>EMAIL_HOST = '$VAR1$' $END$</pre>|
|semail_host_password|<pre>EMAIL_HOST_PASSWORD = '$VAR1$' $END$</pre>|
|semail_host_user|<pre>EMAIL_HOST_USER = '$VAR1$' $END$</pre>|
|semail_port|<pre>EMAIL_PORT = $VAR1$ $END$</pre>|
|semail_ssl_certfile|<pre>EMAIL_SSL_CERTFILE = $VAR1$ $END$</pre>|
|semail_ssl_keyfile|<pre>EMAIL_SSL_KEYFILE = $VAR1$ $END$</pre>|
|semail_subject_prefix|<pre>EMAIL_SUBJECT_PREFIX = '$VAR1$' $END$</pre>|
|semail_timeout|<pre>EMAIL_TIMEOUT = $VAR1$ $END$</pre>|
|semail_use_ssl|<pre>EMAIL_USE_SSL = $VAR1$ $END$</pre>|
|semail_use_tls|<pre>EMAIL_USE_TLS = $VAR1$ $END$</pre>|
|sfile_charset|<pre>FILE_CHARSET = '$VAR1$' $END$</pre>|
|sfile_upload_directory_permissions|<pre>FILE_UPLOAD_DIRECTORY_PERMISSIONS = $VAR1$ $END$</pre>|
|sfile_upload_handlers|<pre>FILE_UPLOAD_HANDLERS = [<br>    'django.core.files.uploadhandler.MemoryFileUploadHandler',<br>    'django.core.files.uploadhandler.TemporaryFileUploadHandler',<br>]$END$</pre>|
|sfile_upload_max_memory_size|<pre>FILE_UPLOAD_MAX_MEMORY_SIZE = $VAR1$ $END$</pre>|
|sfile_upload_permissions|<pre>FILE_UPLOAD_PERMISSIONS = $VAR1$ $END$</pre>|
|sfile_upload_temp_dir|<pre>FILE_UPLOAD_TEMP_DIR = $VAR1$ $END$</pre>|
|sfirst_day_of_week|<pre>FIRST_DAY_OF_WEEK = $VAR1$ $END$</pre>|
|sfixture_dirs|<pre>FIXTURE_DIRS = [$VAR1$] $END$</pre>|
|sforce_script_name|<pre>FORCE_SCRIPT_NAME = $VAR1$ $END$</pre>|
|sformat_module_path|<pre>FORMAT_MODULE_PATH = $VAR1$ $END$</pre>|
|signorable_404_urls|<pre>IGNORABLE_404_URLS = $VAR1$ $END$</pre>|
|sinstalled_apps|<pre>INSTALLED_APPS = $VAR1$ $END$</pre>|
|sinternal_ips|<pre>INTERNAL_IPS = $VAR1$ $END$</pre>|
|slanguage_code|<pre>LANGUAGE_CODE = '$VAR1$' $END$</pre>|
|slanguage_cookie_age|<pre>LANGUAGE_COOKIE_AGE = $VAR1$ $END$</pre>|
|slanguage_cookie_domain|<pre>LANGUAGE_COOKIE_DOMAIN = $VAR1$ $END$</pre>|
|slanguage_cookie_name|<pre>LANGUAGE_COOKIE_NAME = '$VAR1$' $END$</pre>|
|slanguage_cookie_path|<pre>LANGUAGE_COOKIE_PATH = '$VAR1$' $END$</pre>|
|slanguages|<pre>LANGUAGES = [<br>    ('af', gettext_noop('Afrikaans')),<br>    ('ar', gettext_noop('Arabic')),<br>    ('ast', gettext_noop('Asturian')),<br>    ('az', gettext_noop('Azerbaijani')),<br>    ('bg', gettext_noop('Bulgarian')),<br>    ('be', gettext_noop('Belarusian')),<br>    ('bn', gettext_noop('Bengali')),<br>    ('br', gettext_noop('Breton')),<br>    ('bs', gettext_noop('Bosnian')),<br>    ('ca', gettext_noop('Catalan')),<br>    ('cs', gettext_noop('Czech')),<br>    ('cy', gettext_noop('Welsh')),<br>    ('da', gettext_noop('Danish')),<br>    ('de', gettext_noop('German')),<br>    ('dsb', gettext_noop('Lower Sorbian')),<br>    ('el', gettext_noop('Greek')),<br>    ('en', gettext_noop('English')),<br>    ('en-au', gettext_noop('Australian English')),<br>    ('en-gb', gettext_noop('British English')),<br>    ('eo', gettext_noop('Esperanto')),<br>    ('es', gettext_noop('Spanish')),<br>    ('es-ar', gettext_noop('Argentinian Spanish')),<br>    ('es-co', gettext_noop('Colombian Spanish')),<br>    ('es-mx', gettext_noop('Mexican Spanish')),<br>    ('es-ni', gettext_noop('Nicaraguan Spanish')),<br>    ('es-ve', gettext_noop('Venezuelan Spanish')),<br>    ('et', gettext_noop('Estonian')),<br>    ('eu', gettext_noop('Basque')),<br>    ('fa', gettext_noop('Persian')),<br>    ('fi', gettext_noop('Finnish')),<br>    ('fr', gettext_noop('French')),<br>    ('fy', gettext_noop('Frisian')),<br>    ('ga', gettext_noop('Irish')),<br>    ('gd', gettext_noop('Scottish Gaelic')),<br>    ('gl', gettext_noop('Galician')),<br>    ('he', gettext_noop('Hebrew')),<br>    ('hi', gettext_noop('Hindi')),<br>    ('hr', gettext_noop('Croatian')),<br>    ('hsb', gettext_noop('Upper Sorbian')),<br>    ('hu', gettext_noop('Hungarian')),<br>    ('ia', gettext_noop('Interlingua')),<br>    ('id', gettext_noop('Indonesian')),<br>    ('io', gettext_noop('Ido')),<br>    ('is', gettext_noop('Icelandic')),<br>    ('it', gettext_noop('Italian')),<br>    ('ja', gettext_noop('Japanese')),<br>    ('ka', gettext_noop('Georgian')),<br>    ('kk', gettext_noop('Kazakh')),<br>    ('km', gettext_noop('Khmer')),<br>    ('kn', gettext_noop('Kannada')),<br>    ('ko', gettext_noop('Korean')),<br>    ('lb', gettext_noop('Luxembourgish')),<br>    ('lt', gettext_noop('Lithuanian')),<br>    ('lv', gettext_noop('Latvian')),<br>    ('mk', gettext_noop('Macedonian')),<br>    ('ml', gettext_noop('Malayalam')),<br>    ('mn', gettext_noop('Mongolian')),<br>    ('mr', gettext_noop('Marathi')),<br>    ('my', gettext_noop('Burmese')),<br>    ('nb', gettext_noop('Norwegian Bokmål')),<br>    ('ne', gettext_noop('Nepali')),<br>    ('nl', gettext_noop('Dutch')),<br>    ('nn', gettext_noop('Norwegian Nynorsk')),<br>    ('os', gettext_noop('Ossetic')),<br>    ('pa', gettext_noop('Punjabi')),<br>    ('pl', gettext_noop('Polish')),<br>    ('pt', gettext_noop('Portuguese')),<br>    ('pt-br', gettext_noop('Brazilian Portuguese')),<br>    ('ro', gettext_noop('Romanian')),<br>    ('ru', gettext_noop('Russian')),<br>    ('sk', gettext_noop('Slovak')),<br>    ('sl', gettext_noop('Slovenian')),<br>    ('sq', gettext_noop('Albanian')),<br>    ('sr', gettext_noop('Serbian')),<br>    ('sr-latn', gettext_noop('Serbian Latin')),<br>    ('sv', gettext_noop('Swedish')),<br>    ('sw', gettext_noop('Swahili')),<br>    ('ta', gettext_noop('Tamil')),<br>    ('te', gettext_noop('Telugu')),<br>    ('th', gettext_noop('Thai')),<br>    ('tr', gettext_noop('Turkish')),<br>    ('tt', gettext_noop('Tatar')),<br>    ('udm', gettext_noop('Udmurt')),<br>    ('uk', gettext_noop('Ukrainian')),<br>    ('ur', gettext_noop('Urdu')),<br>    ('vi', gettext_noop('Vietnamese')),<br>    ('zh-hans', gettext_noop('Simplified Chinese')),<br>    ('zh-hant', gettext_noop('Traditional Chinese')),<br>]<br>$END$</pre>|
|slanguages_bidi|<pre>LANGUAGES_BIDI = ["he", "ar", "fa", "ur", $VAR1$] $END$</pre>|
|slocale_paths|<pre>LOCALE_PATHS = $VAR1$ $END$</pre>|
|slogfilter|<pre>'$VAR1$': {<br>    '$VAR2$': '$VAR3$',<br>},$END$</pre>|
|slogfiltercallback|<pre>'$VAR1$': {<br>    '()': 'django.utils.log.CallbackFilter',<br>},$END$</pre>|
|slogfilterdebugfalse|<pre>'$VAR1$': {<br>    '()': 'django.utils.log.RequireDebugFalse',<br>},$END$</pre>|
|slogfilterdebugtrue|<pre>'$VAR1$': {<br>    '()': 'django.utils.log.RequireDebugTrue',<br>},$END$</pre>|
|slogformatter|<pre>'$VAR1$': {<br>    '()': '$VAR2$',<br>    'format': '$VAR3$',<br>}$END$</pre>|
|slogformatterserver|<pre>'$VAR1$': {<br>    '()': 'django.utils.log.ServerFormatter',<br>    'format': '$VAR2$',<br>}$END$</pre>|
|slogger|<pre>'$VAR1$': {<br>    'handlers': ['$VAR2$'],<br>    'level': '$VAR3$',<br>    'propagate': $VAR4$,<br>}$END$</pre>|
|slogging|<pre>LOGGING = {<br>    'version': 1,<br>    'disable_existing_loggers': False,<br>    'formatters': {<br>        $VAR1$<br>    },<br>    'filters': {<br>        $VAR2$<br>    },<br>    'handlers': {<br>        $VAR3$<br>    },<br>    'loggers': {<br>        $VAR4$<br>    }<br>}<br>$END$</pre>|
|slogging_config|<pre>LOGGING_CONFIG = '$VAR1$' $END$</pre>|
|sloghandler|<pre>'$VAR1$': {<br>    'level': '$VAR2$',<br>    'filters': ['$VAR3$'],<br>    'class': '$VAR4$',<br>},$END$</pre>|
|sloghandleremail|<pre>'$VAR1$': {<br>    'level': '$VAR2$',<br>    'filters': ['$VAR3$'],<br>    'class': 'django.utils.log.AdminEmailHandler'<br>},$END$</pre>|
|sloghandlerstream|<pre>'$VAR1$': {<br>    'level': '$VAR2$',<br>    'filters': ['$VAR3$'],<br>    'class': 'logging.StreamHandler',<br>},$END$</pre>|
|slogin_redirect_url|<pre>LOGIN_REDIRECT_URL = '$VAR1$' $END$</pre>|
|slogin_url|<pre>LOGIN_URL = '$VAR1$' $END$</pre>|
|slogout_redirect_url|<pre>LOGOUT_REDIRECT_URL = $VAR1$ $END$</pre>|
|smanagers|<pre>MANAGERS = $VAR1$ $END$</pre>|
|smedia_root|<pre>MEDIA_ROOT = '$VAR1$' $END$</pre>|
|smedia_url|<pre>MEDIA_URL = '$VAR1$' $END$</pre>|
|smessage_level|<pre>MESSAGE_LEVEL = $VAR1$ $END$</pre>|
|smessage_storage|<pre>MESSAGE_STORAGE = '$VAR1$' $END$</pre>|
|smessage_tags|<pre>MESSAGE_TAGS = {<br>    messages.DEBUG: '$VAR1$',<br>    messages.INFO: '$VAR2$',<br>    messages.SUCCESS: '$VAR3$',<br>    messages.WARNING: '$VAR4$',<br>    messages.ERROR: '$VAR5$',<br>}<br>$END$</pre>|
|smiddleware|<pre>MIDDLEWARE = [<br>    'django.middleware.security.SecurityMiddleware',<br>    'django.contrib.sessions.middleware.SessionMiddleware',<br>    'django.middleware.common.CommonMiddleware',<br>    'django.middleware.csrf.CsrfViewMiddleware',<br>    'django.contrib.auth.middleware.AuthenticationMiddleware',<br>    'django.contrib.messages.middleware.MessageMiddleware',<br>    'django.middleware.clickjacking.XFrameOptionsMiddleware',<br>]<br>$END$</pre>|
|smiddleware_classes|<pre>MIDDLEWARE_CLASSES = [<br>    'django.middleware.common.CommonMiddleware',<br>    'django.middleware.csrf.CsrfViewMiddleware',<br>    '$VAR1$'<br>]<br>$END$</pre>|
|smigration_modules|<pre>MIGRATION_MODULES = $VAR1$ $END$</pre>|
|smonth_day_format|<pre>MONTH_DAY_FORMAT = '$VAR1$' $END$</pre>|
|snumber_grouping|<pre>NUMBER_GROUPING = $VAR1$ $END$</pre>|
|spassword_hashers|<pre>PASSWORD_HASHERS = [<br>    'django.contrib.auth.hashers.PBKDF2PasswordHasher',<br>    'django.contrib.auth.hashers.PBKDF2SHA1PasswordHasher',<br>    'django.contrib.auth.hashers.Argon2PasswordHasher',<br>    'django.contrib.auth.hashers.BCryptSHA256PasswordHasher',<br>    'django.contrib.auth.hashers.BCryptPasswordHasher',<br>    '$VAR1$'<br>]<br>$END$<br></pre>|
|spassword_reset_timeout_days|<pre>PASSWORD_RESET_TIMEOUT_DAYS = $VAR1$ $END$</pre>|
|sprepend_www|<pre>PREPEND_WWW = $VAR1$ $END$</pre>|
|sroot_urlconf|<pre>ROOT_URLCONF = '$VAR1$'</pre>|
|ssecret_key|<pre>SECRET_KEY = '$VAR1$' $END$</pre>|
|ssecure_browser_xss_filter|<pre>SECURE_BROWSER_XSS_FILTER = $VAR1$ $END$</pre>|
|ssecure_content_type_nosniff|<pre>SECURE_CONTENT_TYPE_NOSNIFF = $VAR1$ $END$</pre>|
|ssecure_hsts_include_subdomains|<pre>SECURE_HSTS_INCLUDE_SUBDOMAINS = $VAR1$ $END$</pre>|
|ssecure_hsts_seconds|<pre>SECURE_HSTS_SECONDS = $VAR1$ $END$</pre>|
|ssecure_proxy_ssl_header|<pre>SECURE_PROXY_SSL_HEADER = $VAR1$ $END$</pre>|
|ssecure_redirect_exempt|<pre>SECURE_REDIRECT_EXEMPT = $VAR1$ $END$</pre>|
|ssecure_ssl_host|<pre>SECURE_SSL_HOST = $VAR1$ $END$</pre>|
|ssecure_ssl_redirect|<pre>SECURE_SSL_REDIRECT = $VAR1$ $END$</pre>|
|sserialization_modules|<pre>SERIALIZATION_MODULES = {'$VAR1$' '$VAR2$'}</pre>|
|sserver_email|<pre>SERVER_EMAIL = '$VAR1$' $END$</pre>|
|ssession_cache_alias|<pre>SESSION_CACHE_ALIAS = '$VAR1$' $END$</pre>|
|ssession_cookie_age|<pre>SESSION_COOKIE_AGE = $VAR1$ $END$</pre>|
|ssession_cookie_domain|<pre>SESSION_COOKIE_DOMAIN = $VAR1$ $END$</pre>|
|ssession_cookie_httponly|<pre>SESSION_COOKIE_HTTPONLY = $VAR1$ $END$</pre>|
|ssession_cookie_name|<pre>SESSION_COOKIE_NAME = '$VAR1$' $END$</pre>|
|ssession_cookie_path|<pre>SESSION_COOKIE_PATH = '$VAR1$' $END$</pre>|
|ssession_cookie_secure|<pre>SESSION_COOKIE_SECURE = $VAR1$ $END$</pre>|
|ssession_engine|<pre>SESSION_ENGINE = '$VAR1$' $END$</pre>|
|ssession_expire_at_browser_close|<pre>SESSION_EXPIRE_AT_BROWSER_CLOSE = $VAR1$ $END$</pre>|
|ssession_file_path|<pre>SESSION_FILE_PATH = $VAR1$ $END$</pre>|
|ssession_save_every_request|<pre>SESSION_SAVE_EVERY_REQUEST = $VAR1$ $END$</pre>|
|ssession_serializer|<pre>SESSION_SERIALIZER = '$VAR1$' $END$</pre>|
|sshort_date_format|<pre>SHORT_DATE_FORMAT = '$VAR1$' $END$</pre>|
|sshort_datetime_format|<pre>SHORT_DATETIME_FORMAT = '$VAR1$' $END$</pre>|
|ssigning_backend|<pre>SIGNING_BACKEND = '$VAR1$' $END$</pre>|
|ssilenced_system_checks|<pre>SILENCED_SYSTEM_CHECKS = $VAR1$ $END$</pre>|
|ssite_id|<pre>SITE_ID = $VAR1$</pre>|
|sstatic_files_finders|<pre>STATICFILES_FINDERS = [<br>    'django.contrib.staticfiles.finders.FileSystemFinder',<br>    'django.contrib.staticfiles.finders.AppDirectoriesFinder',<br>    $VAR1$<br>]<br>$END$<br></pre>|
|sstatic_root|<pre>STATIC_ROOT = $VAR1$ $END$</pre>|
|sstatic_url|<pre>STATIC_URL = '$VAR1$' $END$</pre>|
|sstaticfiles_dirs|<pre>STATICFILES_DIRS = [$VAR1$] $END$</pre>|
|sstaticfiles_storage|<pre>STATICFILES_STORAGE = '$VAR1$' $END$</pre>|
|stemplates|<pre>TEMPLATES = [<br>    {<br>        'BACKEND': '$VAR1$',<br>        'APP_DIRS': $VAR2$,<br>        'DIRS': [<br>            $VAR3$<br>        ],<br>        'OPTIONS': {$VAR4$},<br>    },<br>]<br>$END$<br><br></pre>|
|stest_non_serialized_apps|<pre>TEST_NON_SERIALIZED_APPS = $VAR1$ $END$</pre>|
|stest_runner|<pre>TEST_RUNNER = '$VAR1$' $END$</pre>|
|sthousand_separator|<pre>THOUSAND_SEPARATOR = '$VAR1$' $END$</pre>|
|stime_format|<pre>TIME_FORMAT = '$VAR1$' $END$</pre>|
|stime_input_formats|<pre>TIME_INPUT_FORMATS = [<br>    '%H:%M:%S',<br>    '%H:%M:%S.%f',<br>    '%H:%M',<br>    '$VAR1$'<br>]<br>$END$</pre>|
|stime_zone|<pre>TIME_ZONE = '$VAR1$' $END$</pre>|
|suse_etags|<pre>USE_ETAGS = $VAR1$ $END$</pre>|
|suse_i18n|<pre>USE_I18N = $VAR1$ $END$</pre>|
|suse_l10n|<pre>USE_L10N = $VAR1$ $END$</pre>|
|suse_thousand_separator|<pre>USE_THOUSAND_SEPARATOR = $VAR1$ $END$</pre>|
|suse_tz|<pre>USE_TZ = $VAR1$ $END$</pre>|
|suse_x_forwarded_host|<pre>USE_X_FORWARDED_HOST = $VAR1$ $END$</pre>|
|suse_x_forwarded_port|<pre>USE_X_FORWARDED_PORT = $VAR1$ $END$</pre>|
|swsgi_application|<pre>WSGI_APPLICATION = $VAR1$ $END$</pre>|
|sx_frame_options|<pre>X_FRAME_OPTIONS = '$VAR1$' $END$</pre>|
|syear_month_format|<pre>YEAR_MONTH_FORMAT = '$VAR1$' $END$</pre>|
