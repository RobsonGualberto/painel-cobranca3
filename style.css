// Dados FICTÍCIOS (depois você troca pelo Excel)
const clientesLidiane = [
    { nome: "Luis Fernando", placa: "SYO1J19", diasAtraso: 54, celular: "11982548898" },
    { nome: "Dayane Silva", placa: "SHR1E37", diasAtraso: 52, celular: "82981365051" }
];

const clientesRobson = [
    { nome: "Fabiano Oliveira", placa: "SII1A27", diasAtraso: 48, celular: "62994567424" }
];

// Preencher a tabela
function carregarTabela() {
    const tabelaLidiane = document.getElementById("tabelaLidiane");
    const tabelaRobson = document.getElementById("tabelaRobson");

    clientesLidiane.forEach(cliente => {
        tabelaLidiane.innerHTML += `
            <tr>
                <td>${cliente.nome}</td>
                <td>${cliente.placa}</td>
                <td>${cliente.diasAtraso} dias</td>
                <td>
                    <a href="https://wa.me/55${cliente.celular}?text=Olá ${cliente.nome}, seu contrato (Placa: ${cliente.placa}) está ${cliente.diasAtraso} dias atrasado. Por favor, regularize!" 
                       class="btn btn-success btn-sm" target="_blank">WhatsApp</a>
                    <button class="btn btn-danger btn-sm" onclick="marcarComoPago(this)">Pago</button>
                </td>
            </tr>
        `;
    });

    clientesRobson.forEach(cliente => {
        tabelaRobson.innerHTML += `
            <tr>
                <td>${cliente.nome}</td>
                <td>${cliente.placa}</td>
                <td>${cliente.diasAtraso} dias</td>
                <td>
                    <a href="https://wa.me/55${cliente.celular}?text=Olá ${cliente.nome}, seu contrato (Placa: ${cliente.placa}) está ${cliente.diasAtraso} dias atrasado. Por favor, regularize!" 
                       class="btn btn-success btn-sm" target="_blank">WhatsApp</a>
                    <button class="btn btn-danger btn-sm" onclick="marcarComoPago(this)">Pago</button>
                </td>
            </tr>
        `;
    });
}

// Função para marcar como PAGO
function marcarComoPago(botao) {
    const linha = botao.parentElement.parentElement;
    linha.style.backgroundColor = "#d4edda"; // Muda a cor para verde claro
    botao.disabled = true; // Desativa o botão
    botao.textContent = "✔️ Pago";
}

// Carregar os dados quando a página abrir
window.onload = carregarTabela;