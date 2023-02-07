## API Report File for "amplify-provider-awscloudformation"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

import { $TSAny } from 'amplify-cli-core';
import { $TSContext } from 'amplify-cli-core';
import { $TSObject } from 'amplify-cli-core';
import * as AWS_2 from 'aws-sdk';
import { IAmplifyResource } from 'amplify-cli-core';
import { Template } from 'amplify-cli-core';

// @public (undocumented)
export const cfnRootStackFileName = "root-cloudformation-stack.json";

// Warning: (ae-forgotten-export) The symbol "LocationService" needs to be exported by the entry point index.d.ts
//
// @public (undocumented)
export function getConfiguredLocationServiceClient(context: $TSContext, options?: Record<string, unknown>): Promise<LocationService>;

// Warning: (ae-forgotten-export) The symbol "SSM" needs to be exported by the entry point index.d.ts
//
// @public (undocumented)
export function getConfiguredSSMClient(context: any): Promise<SSM>;

// @public (undocumented)
export const getLocationRegionMapping: () => $TSObject;

// @public (undocumented)
export const getLocationSupportedRegion: (region: string) => string;

// Warning: (ae-forgotten-export) The symbol "AwsSdkConfig" needs to be exported by the entry point index.d.ts
//
// @public (undocumented)
export function loadConfigurationForEnv(context: $TSContext, env: string, appId?: string): Promise<AwsSdkConfig>;

// @public (undocumented)
export const resolveAppId: (context: $TSContext) => string;

// @public (undocumented)
export const rootStackFileName = "root-cloudformation-stack.json";

// @public (undocumented)
export const storeRootStackTemplate: (context: $TSContext, template?: Template) => Promise<void>;

// @public (undocumented)
export const transformResourceWithOverrides: (context: $TSContext, resource?: IAmplifyResource) => Promise<void>;

// (No @packageDocumentation comment for this package)

```