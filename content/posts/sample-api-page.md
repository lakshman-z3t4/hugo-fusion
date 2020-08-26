---
author: "Lakshman"
date: 2014-09-28
linktitle: Sample API Page
menu:
  main:
    parent: API
title: Sample API Page
reading_time: 12 mins
weight: 10
---

{{< details title="INDIVIDUAL APPLICATION" >}}

  {{< api_requests 
  type="GET" 
  title="GET"
  req_link="/api/v1/ifi/{ifiID}/applications"
  req_desc="Get Individual Application Request."
  req_content="Returns list of Individual Application Response object."
  >}}

  {{< api_parameters >}}
      {{< api_params
      name="ifiID *"
      var_type="integer"
      param_type="(path)"
      description="ID of the IFI (onboarded organization) under which the Individual Application Request is being retrieved."
      >}}{{< /api_params >}}
      
      {{< api_params
      name="status"
      var_type="string"
      param_type="(query)"
      description="Status of the Individual Application Request being retrieved. Available values : PROCESSING, PENDING_ON_USER_ACTION, IN_REVIEW, REJECTED, APPROVED, DELETED"
      >}}{{< /api_params >}}

      {{< api_params
      name="pageNumber"
      var_type="integer"
      param_type="(query)"
      description="Page being requested."
      >}}{{< /api_params >}}

      {{< api_params
      name="pageSize"
      var_type="integer"
      param_type="(query)"
      description="Defines the number of items to be displayed on one page."
      >}}{{< /api_params >}}
  {{< /api_parameters >}}

  {{< api_request_body
  name="pageSize"
  var_type="integer"
  param_type="(query)"
  description="Defines the number of items to be displayed on one page."
  >}}{{< /api_request_body >}}

  {{< /api_requests >}}

  
{{< /details >}}

{{< api_requests 
  type="GET" 
  title="GET"
  req_link="/api/v1/ifi/{ifiID}/applications"
  req_desc="Get Individual Application Request."
  req_content="Returns list of Individual Application Response object."
  >}}

  {{< api_parameters >}}
      {{< api_params
      name="ifiID *"
      var_type="integer"
      param_type="(path)"
      description="ID of the IFI (onboarded organization) under which the Individual Application Request is being retrieved."
      >}}{{< /api_params >}}
      
      {{< api_params
      name="status"
      var_type="string"
      param_type="(query)"
      description="Status of the Individual Application Request being retrieved. Available values : PROCESSING, PENDING_ON_USER_ACTION, IN_REVIEW, REJECTED, APPROVED, DELETED"
      >}}{{< /api_params >}}

      {{< api_params
      name="pageNumber"
      var_type="integer"
      param_type="(query)"
      description="Page being requested."
      >}}{{< /api_params >}}

      {{< api_params
      name="pageSize"
      var_type="integer"
      param_type="(query)"
      description="Defines the number of items to be displayed on one page."
      >}}{{< /api_params >}}
  {{< /api_parameters >}}

  {{< api_request_body
  name="pageSize"
  var_type="integer"
  param_type="(query)"
  description="Defines the number of items to be displayed on one page."
  >}}{{< /api_request_body >}}

  {{< /api_requests >}}

  {{< api_requests 
  type="PUT" 
  title="PUT"
  req_link="​/api​/v1​/ifi​/{ifiID}​/individualApplications​/{applicationID}"
  req_desc="Update Individual Application Request."
  req_content="Returns list of Individual Application Response object."
  >}}

  {{< api_parameters >}}
      {{< api_params
      name="ifiID *"
      var_type="integer"
      param_type="(path)"
      description="ID of the IFI (onboarded organization) under which the Individual Application Request is being retrieved."
      >}}{{< /api_params >}}
      
      {{< api_params
      name="status"
      var_type="string"
      param_type="(query)"
      description="Status of the Individual Application Request being retrieved. Available values : PROCESSING, PENDING_ON_USER_ACTION, IN_REVIEW, REJECTED, APPROVED, DELETED"
      >}}{{< /api_params >}}

      {{< api_params
      name="pageNumber"
      var_type="integer"
      param_type="(query)"
      description="Page being requested."
      >}}{{< /api_params >}}

      {{< api_params
      name="pageSize"
      var_type="integer"
      param_type="(query)"
      description="Defines the number of items to be displayed on one page."
      >}}{{< /api_params >}}
  {{< /api_parameters >}}

  {{< api_request_body
  name="pageSize"
  var_type="integer"
  param_type="(query)"
  description="Defines the number of items to be displayed on one page."
  >}}{{< /api_request_body >}}

  {{< /api_requests >}}


  {{< api_requests 
  type="DELETE" 
  title="DELETE"
  req_link="/api​/v1​/ifi​/{ifiID}​/individualApplications​/{applicationID}"
  req_desc="Delete Individual Application Request."
  req_content="Returns list of Individual Application Response object."
  >}}

  {{< api_parameters >}}
      {{< api_params
      name="ifiID *"
      var_type="integer"
      param_type="(path)"
      description="ID of the IFI (onboarded organization) under which the Individual Application Request is being retrieved."
      >}}{{< /api_params >}}
      
      {{< api_params
      name="status"
      var_type="string"
      param_type="(query)"
      description="Status of the Individual Application Request being retrieved. Available values : PROCESSING, PENDING_ON_USER_ACTION, IN_REVIEW, REJECTED, APPROVED, DELETED"
      >}}{{< /api_params >}}

      {{< api_params
      name="pageNumber"
      var_type="integer"
      param_type="(query)"
      description="Page being requested."
      >}}{{< /api_params >}}

      {{< api_params
      name="pageSize"
      var_type="integer"
      param_type="(query)"
      description="Defines the number of items to be displayed on one page."
      >}}{{< /api_params >}}
  {{< /api_parameters >}}

  {{< api_request_body
  name="pageSize"
  var_type="integer"
  param_type="(query)"
  description="Defines the number of items to be displayed on one page."
  >}}{{< /api_request_body >}}

  {{< /api_requests >}}


  {{< api_requests 
  type="POST" 
  title="POST"
  req_link="/api/v1/ifi/{ifiID}/applications"
  req_desc="Create Individual Application Request"
  req_content="Returns list of Individual Application Response object."
  >}}

  {{< api_parameters >}}
      {{< api_params
      name="ifiID *"
      var_type="integer"
      param_type="(path)"
      description="ID of the IFI (onboarded organization) under which the Individual Application Request is being retrieved."
      >}}{{< /api_params >}}
      
      {{< api_params
      name="status"
      var_type="string"
      param_type="(query)"
      description="Status of the Individual Application Request being retrieved. Available values : PROCESSING, PENDING_ON_USER_ACTION, IN_REVIEW, REJECTED, APPROVED, DELETED"
      >}}{{< /api_params >}}

      {{< api_params
      name="pageNumber"
      var_type="integer"
      param_type="(query)"
      description="Page being requested."
      >}}{{< /api_params >}}

      {{< api_params
      name="pageSize"
      var_type="integer"
      param_type="(query)"
      description="Defines the number of items to be displayed on one page."
      >}}{{< /api_params >}}
  {{< /api_parameters >}}

  {{< api_request_body
  name="pageSize"
  var_type="integer"
  param_type="(query)"
  description="Defines the number of items to be displayed on one page."
  >}}{{< /api_request_body >}}

  {{< /api_requests >}}


<!-- {{< details title="Title" >}}
## eteadg
  {{< details title="Title 2">}} 
  ## gddg
    {{< details title="Title 3">}} 
      <p style="background: blue">test</p>
    {{< /details >}} 
  {{< /details >}}
{{< /details >}} -->