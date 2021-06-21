## API Report File for "@backstage/plugin-kubernetes"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

import { ApiRef } from '@backstage/core';
import { BackstagePlugin } from '@backstage/core';
import { Entity } from '@backstage/catalog-model';
import { KubernetesRequestBody } from '@backstage/plugin-kubernetes-common';
import { OAuthApi } from '@backstage/core';
import { RouteRef } from '@backstage/core';

// @public (undocumented)
export const EntityKubernetesContent: (_props: {
    entity?: Entity| undefined;
}) => JSX.Element;

// @public (undocumented)
export class KubernetesAuthProviders implements KubernetesAuthProvidersApi {
    constructor(options: {
        googleAuthApi: OAuthApi;
    });
    // (undocumented)
    decorateRequestBodyForAuth(authProvider: string, requestBody: KubernetesRequestBody): Promise<KubernetesRequestBody>;
    }

// @public (undocumented)
export const kubernetesAuthProvidersApiRef: ApiRef<KubernetesAuthProvidersApi>;

// @public (undocumented)
const kubernetesPlugin: BackstagePlugin<{
    entityContent: RouteRef<undefined>;
}, {}>;

export { kubernetesPlugin }

export { kubernetesPlugin as plugin }

// @public (undocumented)
export const Router: (_props: Props) => JSX.Element;


// (No @packageDocumentation comment for this package)

```