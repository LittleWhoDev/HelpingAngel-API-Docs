# DefaultApi

All URIs are relative to *http://localhost:3000*

Method | HTTP request | Description
------------- | ------------- | -------------
[**getPosts**](DefaultApi.md#getPosts) | **GET** /posts | Search posts
[**getPostsPostId**](DefaultApi.md#getPostsPostId) | **GET** /posts/{postId} | Get individual Post
[**postPosts**](DefaultApi.md#postPosts) | **POST** /posts | 
[**putPostsPostId**](DefaultApi.md#putPostsPostId) | **PUT** /posts/{postId} | 


<a name="getPosts"></a>
# **getPosts**
> List getPosts(content, range, location, category, type)

Search posts

    Search and filter posts

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **content** | **String**| Full text search | [optional] [default to null]
 **range** | **Integer**| KM range around \&quot;location\&quot; | [optional] [default to null]
 **location** | **String**| Current location | [optional] [default to null]
 **category** | **String**| Post category | [optional] [default to null]
 **type** | **String**| Post type | [optional] [default to null]

### Return type

[**List**](..//Models/Post.md)

### Authorization

[Standard](../README.md#Standard)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getPostsPostId"></a>
# **getPostsPostId**
> Post getPostsPostId(postId, body)

Get individual Post

    Get individual post

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **postId** | **String**|  | [default to null]
 **body** | **Object**|  | [optional]

### Return type

[**Post**](..//Models/Post.md)

### Authorization

[Standard](../README.md#Standard)

### HTTP request headers

- **Content-Type**: application/json, application/xml
- **Accept**: application/json

<a name="postPosts"></a>
# **postPosts**
> postPosts(post)



    Create a new post

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **post** | [**Post**](..//Models/Post.md)|  | [optional]

### Return type

null (empty response body)

### Authorization

[Standard](../README.md#Standard)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

<a name="putPostsPostId"></a>
# **putPostsPostId**
> putPostsPostId(postId, post)



    Update post

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **postId** | **String**|  | [default to null]
 **post** | [**Post**](..//Models/Post.md)|  | [optional]

### Return type

null (empty response body)

### Authorization

[Standard](../README.md#Standard)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

