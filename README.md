# Silent Errors in React Native useEffect Cleanup Functions

This repository demonstrates a subtle bug in React Native where errors thrown within the cleanup function of a `useEffect` hook might not be properly reported, making debugging difficult. The error occurs when attempting to unsubscribe from a stream or close a resource that's already been closed.