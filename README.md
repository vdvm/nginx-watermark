# Nginx HttpImageFilterModule with watermark support

Tested with nginx 1.4.3


Usage:

image_filter watermark {path to PNG watermark file} [bottom-right|top-left|top-right|bottom-left|center];

Position default: bottom-right

See also http://nginx.org/en/docs/http/ngx_http_image_filter_module.html#image_filter_buffer

