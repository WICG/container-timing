# Shadow DOM

Accessing Shadow DOM and getting paint events is outside the realm of Container Timing and something which isn't possible. That said, setting `elementtiming` on the shadow root does yield an element-timing event when the content has rendered. We should discuss this.
