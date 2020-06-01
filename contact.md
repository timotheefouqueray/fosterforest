<body class="bg-light">
    <div class="container">
        <div class="py-5 text-center">
            <h2>Contact</h2>
        </div>
        <div class="row">
            <div class="col-md-12 order-md-1">
                <h4 class="mb-3">Envie d'en savoir plus ?</h4>
                <form class="needs-validation" id="contact-form" action="https://formspree.io/xzbjrzbr" method="POST"
                    novalidate>
                    <div class="mb-3">
                        <label for="_replyto" class="required-label">E-mail</label>
                        <input type="email" class="form-control" id="_replyto" name="_replyto" placeholder="" required>
                        <div class="invalid-feedback">
                            Veullez entrer votre adresse e-mail
                        </div>
                    </div>
                    <div class="mb-3">
                        <label for="contactMessage" class="required-label">Votre message</label>
                        <textarea class="form-control" id="contactMessage" name="contactMessage" placeholder=""
                            required></textarea>
                        <div class="invalid-feedback">
                            Veuillez entrez votre message
                        </div>
                    </div>
                    <hr class="mb-4">
                    <button class="btn btn-primary btn-lg btn-block" type="submit" id="submit-btn">Envoyer</button>
                </form>
            </div>
        </div>
    </div>
</body>
