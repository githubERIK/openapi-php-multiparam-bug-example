# OpenAPI\Client\DefaultApi

All URIs are relative to *https://some.example.api.com/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**fetchNotes**](DefaultApi.md#fetchNotes) | **GET** /notes | Returns all notes.


# **fetchNotes**
> fetchNotes($label_ids)

Returns all notes.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$label_ids = array('label_ids_example'); // string[] | 

try {
    $apiInstance->fetchNotes($label_ids);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->fetchNotes: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **label_ids** | [**string[]**](../Model/string.md)|  | [optional]

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

