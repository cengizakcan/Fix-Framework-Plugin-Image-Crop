# Fix-Framework-Image-Crop


# TUTORIAL

		$this->plugin("image/crop");

		$resim = new crop;

		$resim->image("app/storage/deneme.jpg") // resim adresi
			->targetw(uzunluk)
			->targeth(yükseklik)
			->xcor(konum x)
			->ycor(konum y)
			->width(uzunluk)
			->height(yükseklik)
			->quality(100) // kalite
			->run();
