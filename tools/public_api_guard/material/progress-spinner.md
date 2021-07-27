## API Report File for "components-srcs"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

import { AbstractConstructor } from '@angular/material/core/common-behaviors/constructor';
import { CanColor } from '@angular/material/core';
import { Constructor } from '@angular/material/core/common-behaviors/constructor';
import { ElementRef } from '@angular/core';
import * as i0 from '@angular/core';
import * as i2 from '@angular/material/core';
import * as i3 from '@angular/common';
import { InjectionToken } from '@angular/core';
import { NumberInput } from '@angular/cdk/coercion';
import { OnInit } from '@angular/core';
import { Platform } from '@angular/cdk/platform';

// @public
export const MAT_PROGRESS_SPINNER_DEFAULT_OPTIONS: InjectionToken<MatProgressSpinnerDefaultOptions>;

// @public
export function MAT_PROGRESS_SPINNER_DEFAULT_OPTIONS_FACTORY(): MatProgressSpinnerDefaultOptions;

// @public
export class MatProgressSpinner extends _MatProgressSpinnerBase implements OnInit, CanColor {
    constructor(elementRef: ElementRef<HTMLElement>, platform: Platform, _document: any, animationMode: string, defaults?: MatProgressSpinnerDefaultOptions);
    get diameter(): number;
    set diameter(size: number);
    _getCircleRadius(): number;
    _getCircleStrokeWidth(): number;
    _getStrokeCircumference(): number;
    _getStrokeDashOffset(): number | null;
    _getViewBox(): string;
    mode: ProgressSpinnerMode;
    // (undocumented)
    static ngAcceptInputType_diameter: NumberInput;
    // (undocumented)
    static ngAcceptInputType_strokeWidth: NumberInput;
    // (undocumented)
    static ngAcceptInputType_value: NumberInput;
    // (undocumented)
    ngOnInit(): void;
    _noopAnimations: boolean;
    _spinnerAnimationLabel: string;
    get strokeWidth(): number;
    set strokeWidth(value: number);
    get value(): number;
    set value(newValue: number);
    // (undocumented)
    static ɵcmp: i0.ɵɵComponentDeclaration<MatProgressSpinner, "mat-progress-spinner", ["matProgressSpinner"], { "color": "color"; "diameter": "diameter"; "strokeWidth": "strokeWidth"; "mode": "mode"; "value": "value"; }, {}, never, never>;
    // (undocumented)
    static ɵfac: i0.ɵɵFactoryDeclaration<MatProgressSpinner, [null, null, { optional: true; }, { optional: true; }, null]>;
}

// @public
export interface MatProgressSpinnerDefaultOptions {
    diameter?: number;
    _forceAnimations?: boolean;
    strokeWidth?: number;
}

// @public (undocumented)
export class MatProgressSpinnerModule {
    // (undocumented)
    static ɵfac: i0.ɵɵFactoryDeclaration<MatProgressSpinnerModule, never>;
    // (undocumented)
    static ɵinj: i0.ɵɵInjectorDeclaration<MatProgressSpinnerModule>;
    // (undocumented)
    static ɵmod: i0.ɵɵNgModuleDeclaration<MatProgressSpinnerModule, [typeof i1.MatProgressSpinner, typeof i1.MatSpinner], [typeof i2.MatCommonModule, typeof i3.CommonModule], [typeof i1.MatProgressSpinner, typeof i1.MatSpinner, typeof i2.MatCommonModule]>;
}

// @public
export class MatSpinner extends MatProgressSpinner {
    constructor(elementRef: ElementRef<HTMLElement>, platform: Platform, document: any, animationMode: string, defaults?: MatProgressSpinnerDefaultOptions);
    // (undocumented)
    static ɵcmp: i0.ɵɵComponentDeclaration<MatSpinner, "mat-spinner", never, { "color": "color"; }, {}, never, never>;
    // (undocumented)
    static ɵfac: i0.ɵɵFactoryDeclaration<MatSpinner, [null, null, { optional: true; }, { optional: true; }, null]>;
}

// @public
export type ProgressSpinnerMode = 'determinate' | 'indeterminate';

// (No @packageDocumentation comment for this package)

```