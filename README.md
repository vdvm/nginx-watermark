# Nginx HttpImageFilterModule with watermark support

## Usage:

```
image_filter watermark /path/to/watermark.png [ bottom-right (default) | top-left | top-right | bottom-left | center ];
```

See also http://nginx.org/en/docs/http/ngx_http_image_filter_module.html#image_filter



## nginx-watermark.patch
For using in spec directly
```
...
%define with_watermark 1
...
%if 0%{?with_watermark}
# PATCH for watermarks
Patch7:         nginx-watermark.patch
%endif
...
```

