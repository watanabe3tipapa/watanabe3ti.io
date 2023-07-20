---
description: I'll try different things and write them down.
---

# 📋 sketchbook

### ちょっと落書き



<mark style="background-color:blue;">**Drawing**</mark>

<img src=".gitbook/assets/file.drawing.svg" alt="GitBook " class="gitbook-drawing">



<mark style="background-color:blue;">**`Code Block`**</mark>

```
/*
 * Allocate NMEMB instances of SIZE bytes and return the pointer, or error on
 * integer overflow.
 */
void *
grub_calloc (grub_size_t nmemb, grub_size_t size)
{
  void *ret;
  grub_size_t sz = 0;

  if (grub_mul (nmemb, size, &sz))
    {
      grub_error (GRUB_ERR_OUT_OF_RANGE, N_("overflow is detected"));
      return NULL;
    }

  ret = grub_memalign (0, sz);
  if (!ret)
    return NULL;

  grub_memset (ret, 0, sz);
  return ret;
}
```



<mark style="background-color:blue;">**Table**</mark>

<table><thead><tr><th width="150" data-type="checkbox"></th><th data-type="number"></th><th width="150" data-type="select"></th><th></th><th></th><th></th><th></th></tr></thead><tbody><tr><td>true</td><td>null</td><td></td><td></td><td></td><td></td><td></td></tr><tr><td>true</td><td>null</td><td></td><td></td><td></td><td></td><td></td></tr><tr><td>true</td><td>null</td><td></td><td></td><td></td><td></td><td></td></tr><tr><td>true</td><td>null</td><td></td><td></td><td></td><td></td><td></td></tr></tbody></table>



<mark style="background-color:blue;">**Math & TeX**</mark>

$$
f(x) = x * e^{2 pi }
$$

$$
e = m* c^2
$$

<mark style="background-color:blue;">**API method**</mark>

{% swagger method="get" path="" baseUrl="" summary="" %}
{% swagger-description %}

{% endswagger-description %}
{% endswagger %}

*

<mark style="background-color:blue;">**Open API**</mark>

/



<mark style="background-color:purple;">**external link**</mark>

> caution&#x20;
>
> 以下は、リンクを示すものであり、当該の方法でColabに接続することは禁じられています

{% embed url="https://github.com/watanabe3tipapa/GoogleColaboratory/blob/main/method4colab_ssh.ipynb" %}
GitHub
{% endembed %}

{% embed url="https://colab.research.google.com/drive/11Z0pIir1mHzNyUGGt2OZpyK8MeSbFnff" %}
Google Drive
{% endembed %}



