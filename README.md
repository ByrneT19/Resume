# Resume
function ContactInfo(cont) {
        console.log(cont);
        return (
            <section>
                {cont.children}
            </section>
        );
    }
    ReactDOM.render(
        <ContactInfo className='infoHead'>
        <h2>Contanct Info:</h2>
        </ContactInfo>,                       
        document.querySelector('#contact')
    );