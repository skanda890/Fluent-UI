## API Report File for "@fluentui/react-infobutton"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

/// <reference types="react" />

import type { ComponentProps } from '@fluentui/react-utilities';
import type { ComponentState } from '@fluentui/react-utilities';
import { ForwardRefComponent } from '@fluentui/react-utilities';
import type { PopoverProps } from '@fluentui/react-popover';
import type { PopoverSurface } from '@fluentui/react-popover';
import * as React_2 from 'react';
import type { Slot } from '@fluentui/react-utilities';
import type { SlotClassNames } from '@fluentui/react-utilities';

// @public
export const InfoButton: ForwardRefComponent<InfoButtonProps>;

// @public (undocumented)
export const infoButtonClassNames: SlotClassNames<InfoButtonSlots>;

// @public
export type InfoButtonProps = Omit<ComponentProps<Partial<InfoButtonSlots>>, 'disabled'> & {
    size?: 'small' | 'medium' | 'large';
};

// @public (undocumented)
export type InfoButtonSlots = {
    root: NonNullable<Slot<'button'>>;
    popover: NonNullable<Slot<PopoverProps>>;
    content: NonNullable<Slot<typeof PopoverSurface>>;
};

// @public
export type InfoButtonState = ComponentState<InfoButtonSlots> & Required<Pick<InfoButtonProps, 'size'>>;

// @public
export const renderInfoButton_unstable: (state: InfoButtonState) => JSX.Element;

// @public
export const useInfoButton_unstable: (props: InfoButtonProps, ref: React_2.Ref<HTMLElement>) => InfoButtonState;

// @public
export const useInfoButtonStyles_unstable: (state: InfoButtonState) => InfoButtonState;

// (No @packageDocumentation comment for this package)

```