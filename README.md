        public static void GhostmonkeMod()
        {
            bool rightControllerPrimaryButton = ControllerInputPoller.instance.rightControllerSecondaryButtonTouch;
            if (rightControllerPrimaryButton)
            {
                GorillaTagger.Instance.offlineVRRig.enabled = false;
            }
            else
            {
                GorillaTagger.Instance.offlineVRRig.enabled = true;
            }
        }
    }
}
