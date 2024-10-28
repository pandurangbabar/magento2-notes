#  Get image url
```
<?php

namespace Pmb\ImageUrl\Block;

use Magento\Framework\View\Element\Template;

class ImageUrl extends Template
{
    /**
     * @var Magento\Framework\View\Asset\Repository
     */
    private $assetRepository;

    /**
     * Construct function
     *
     * @param Template\Context $context
     * @param \Magento\Framework\View\Asset\Repository $assetRepository
     * @param array $data
     */
    public function __construct(
        Template\Context $context,
        \Magento\Framework\View\Asset\Repository $assetRepository,
        array $data = []
    ) {
        $this->assetRepository = $assetRepository;
        parent::__construct($context, $data);
    }

    /**
     * Returns action url for contact form
     *
     * @return string
     */
    public function getImageUrl()
    {
        $imageUrl = $this->assetRepository->getUrl('Pmb_ImageUrl::images/magento2-logo.png');
        return $imageUrl;
    }
}
```
## About me ##
I am a Magento 2 developer with 10+ years of experience. Please feel free to contact me, if you need Magento 2 development help.

* Email - pandurangmbabar5@gamil.com
* Skype - live:pandurang.babar
