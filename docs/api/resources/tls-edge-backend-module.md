import TLSEdgeBackendModuleReplaceRequest from './examples/_tls_edge_backend_module_replace_request.md';
import TLSEdgeBackendModuleReplaceResponse from './examples/_tls_edge_backend_module_replace_response.md';
import TLSEdgeBackendModuleGetRequest from './examples/_tls_edge_backend_module_get_request.md';
import TLSEdgeBackendModuleGetResponse from './examples/_tls_edge_backend_module_get_response.md';
import TLSEdgeBackendModuleDeleteRequest from './examples/_tls_edge_backend_module_delete_request.md';

# TLS Edge Backend
------------



## Replace TLS Edge Backend Module


### Request

PUT /edges/tls/{id}/backend

<TLSEdgeBackendModuleReplaceRequest />


#### Parameters

|&nbsp;| &nbsp;| &nbsp;|
|---|---|---|
| `enabled` | boolean | `true` if the module will be applied to traffic, `false` to disable. default `true` if unspecified |
| `backend_id` | string | backend to be used to back this endpoint |


### Response

Returns a 200 response  on success

<TLSEdgeBackendModuleReplaceResponse />


#### Fields

|&nbsp;| &nbsp;| &nbsp;|
|---|---|---|
| `enabled` | boolean | `true` if the module will be applied to traffic, `false` to disable. default `true` if unspecified |
| `backend` | [Ref](#api-tls-edge-backend-module-replace-fields-ref) | backend to be used to back this endpoint |

#### Ref fields

|&nbsp;| &nbsp;| &nbsp;|
|---|---|---|
| `id` | string | a resource identifier |
| `uri` | string | a uri for locating a resource |


## Get TLS Edge Backend Module


### Request

GET /edges/tls/{id}/backend

<TLSEdgeBackendModuleGetRequest />


### Response

Returns a 200 response  on success

<TLSEdgeBackendModuleGetResponse />


#### Fields

|&nbsp;| &nbsp;| &nbsp;|
|---|---|---|
| `enabled` | boolean | `true` if the module will be applied to traffic, `false` to disable. default `true` if unspecified |
| `backend` | [Ref](#api-tls-edge-backend-module-get-fields-ref) | backend to be used to back this endpoint |

#### Ref fields

|&nbsp;| &nbsp;| &nbsp;|
|---|---|---|
| `id` | string | a resource identifier |
| `uri` | string | a uri for locating a resource |


## Delete TLS Edge Backend Module


### Request

DELETE /edges/tls/{id}/backend

<TLSEdgeBackendModuleDeleteRequest />


### Response

Returns a 204 response with no body on success